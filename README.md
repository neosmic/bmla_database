# bmla_database
Binary model layer for Arango DB in PHP

Se debe crear una clase BinarySettings con las siguientes propiedades:
   ` <?php

   namespace App\Models;

    class BinarySettings
    {
    public static $main_node = "MAIN";
    public static $nodesCollection = "library";
    public static $edgesCollection = "links";
    public static $_tags = [];
    public static $_leaves = [];
    public static $_utc = 0;
    public static $setted = false;
    /********************** DB configuration****************** */
    protected $db_name = '<NOMBRE DE BASE DE DATOS>';
    protected $db_server = '<DIRECCION EN TCP Y PUERTO EJ: tcp:127.0.0.1:2599>';
    protected $db_user = '<NOMBRE DE USUARIO>';
    protected $db_user_pass = '<PASSWORD DE USUARIO>';
    }
    
    
