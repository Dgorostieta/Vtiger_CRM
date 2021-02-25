# Vtiger_CRM
Requerimiento para Vtiger


    Apache 2.1+
    MySQL 5.1+
        storage_engine = InnoDB
        local_infile = ON (under [mysqld] section)
        sql_mode = empty (or NO_ENGINE_SUBSTITUTION) for MySQL 5.6+
    PHP 5.2+, 7.0+
        php-imap
        php-curl
        php-xml
        memory_limit (min. 256MB)
        max_execution_time (min. 60 seconds)
        error_reporting (E_ERROR & ~E_NOTICE & ~E_STRICT & ~E_DEPRECATED)
        display_errors = OFF
        short_open_tag = OFF
    Hardware: 4 GB RAM, 250 GB Disk (for file attachments)
