<?php
return [
    'MAGE_MODE' => getenv('MAGE_MODE'),
    'x-frame-options' => 'SAMEORIGIN',
    'install' => [
        'date' => 'Fri, 14 Jan 2022 18:39:39 +0000'
    ],
    'downloadable_domains' => [
        'www.magento.lan'
    ],
    'backend' => [
        'frontName' => 'admin'
    ],
    'crypt' => [
        'key' => '030bf837c0fd8baa0b1d20d7ea96f1a9'
    ],
    'resource' => [
        'default_setup' => [
            'connection' => 'default'
        ]
    ],
    'remote_storage' => [
        'driver' => 'file'
    ],
    'queue' => [
        'consumers_wait_for_messages' => 1
    ],
    'db' => [
        'connection' => [
            'indexer' => [
                'host' => getenv('MYSQL_HOST'),
                'dbname' => getenv('MYSQL_DATABASE'),
                'username' => getenv('MYSQL_USER'),
                'password' => getenv('MYSQL_PASSWORD'),
                'model' => 'mysql4',
                'engine' => 'innodb',
                'initStatements' => 'SET NAMES utf8;',
                'active' => '1',
                'persistent' => null
            ],
            'default' => [
                'host' => getenv('MYSQL_HOST'),
                'dbname' => getenv('MYSQL_DATABASE'),
                'username' => getenv('MYSQL_USER'),
                'password' => getenv('MYSQL_PASSWORD'),
                'model' => 'mysql4',
                'engine' => 'innodb',
                'initStatements' => 'SET NAMES utf8;',
                'active' => '1',
                'driver_options' => [
                    1014 => false
                ]
            ]
        ],
        'table_prefix' => ''
    ],
    'session' => [
        'save' => 'redis',
        'redis' => [
            'server' => getenv('REDIS_SESSION_HOST'),
            'port' => getenv('REDIS_SESSION_PORT'),
            'password' => '',
            'timeout' => '2.5',
            'persistent_identifier' => '',
            'database' => '2',
            'compression_threshold' => '2048',
            'compression_library' => 'gzip',
            'log_level' => '4',
            'max_concurrency' => '6',
            'break_after_frontend' => '5',
            'break_after_adminhtml' => '30',
            'first_lifetime' => '600',
            'bot_first_lifetime' => '60',
            'bot_lifetime' => '7200',
            'disable_locking' => '0',
            'min_lifetime' => '60',
            'max_lifetime' => '2592000',
            'sentinel_master' => '',
            'sentinel_servers' => '',
            'sentinel_connect_retries' => '5',
            'sentinel_verify_master' => '0'
        ]
    ],
    'cache' => [
        'frontend' => [
            'default' => [
                'backend' => 'Magento\\Framework\\Cache\\Backend\\Redis',
                'backend_options' => [
                    'server' => getenv('REDIS_CACHE_HOST'),
                    'port' => getenv('REDIS_CACHE_PORT'),
                    'database' => '0',
                    'password' => '',
                    'compress_data' => '1',
                    'compression_lib' => '',
                    'preload_keys' => [
                        'EAV_ENTITY_TYPES',
                        'GLOBAL_PLUGIN_LIST',
                        'DB_IS_UP_TO_DATE',
                        'SYSTEM_DEFAULT'
                    ]
                ]
            ],
            'page_cache' => [
                'backend' => 'Magento\\Framework\\Cache\\Backend\\Redis',
                'backend_options' => [
                    'server' => getenv('REDIS_CACHE_HOST'),
                    'port' => getenv('REDIS_CACHE_PORT'),
                    'database' => '1',
                    'password' => '',
                    'compress_data' => '0',
                    'compression_lib' => ''
                ]
            ]
        ],
        'allow_parallel_generation' => false
    ],
    'lock' => [
        'provider' => 'db',
        'config' => [
            'prefix' => ''
        ]
    ],
    'directories' => [
        'document_root_is_pub' => true
    ],
    'cache_types' => [
        'config' => 1,
        'layout' => 1,
        'block_html' => 1,
        'collections' => 1,
        'reflection' => 1,
        'db_ddl' => 1,
        'compiled_config' => 1,
        'eav' => 1,
        'customer_notification' => 1,
        'config_integration' => 1,
        'config_integration_api' => 1,
        'full_page' => 1,
        'target_rule' => 1,
        'config_webservice' => 1,
        'translate' => 1,
        'vertex' => 1
    ],
];
