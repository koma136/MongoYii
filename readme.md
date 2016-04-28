
WORK GRIDFS PHP7!!!

Fork sammaye/mongoyii

Install: 
pecl install mongodb 

composer ruquire mongofill/mongofill 

composer ruquire koma136/MongoYii


use:

'components' => [

        'mongodb' => [

            'class' => 'EMongoClient',

            'server' => 'mongodb://root:root@localhost',

            'db' => 'parser'

        ],

]        

$file = EMongoFile::model()->findOne(
                [
                    'filename' => 'test'
                ]
            );
