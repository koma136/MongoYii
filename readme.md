
WORK GRIDFS PHP7!!!

Fork sammaye/mongoyii

Install: 
pecl install mongodb \n
composer ruquire mongofill/mongofill \n
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
