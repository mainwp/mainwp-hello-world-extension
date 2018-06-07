=== Example Extension ===

* Fetch data from mainwp 
Filter "mainwp-getsites": Fetch child-sites data. 
   

* Call function on child-plugin
Filter "mainwp_fetchurlauthed": call function get_all_posts on child-plugin

Other available functions on child-plugin:
    $callableFunctions = array(
        'stats' => 'getSiteStats',
        'upgrade' => 'upgradeWP',
        'newpost' => 'newPost',
        'deactivate' => 'deactivate',
        'newuser' => 'newUser',
        'newadminpassword' => 'newAdminPassword',
        'installplugintheme' => 'installPluginTheme',
        'upgradeplugintheme' => 'upgradePluginTheme',
        'backup' => 'backup',
        'backup_checkpid' => 'backup_checkpid',
        'cloneinfo' => 'cloneinfo',
        'security' => 'getSecurityStats',
        'securityFix' => 'doSecurityFix',
        'securityUnFix' => 'doSecurityUnFix',
        'post_action' => 'post_action',
        'get_all_posts' => 'get_all_posts',
        'comment_action' => 'comment_action',
        'comment_bulk_action' => 'comment_bulk_action',
        'get_all_comments' => 'get_all_comments',
        'get_all_themes' => 'get_all_themes',
        'theme_action' => 'theme_action',
        'get_all_plugins' => 'get_all_plugins',
        'plugin_action' => 'plugin_action',
        'get_all_pages' => 'get_all_pages',
        'get_all_users' => 'get_all_users',
        'user_action' => 'user_action',
        'search_users' => 'search_users',
        'get_terms' => 'get_terms',
        'set_terms' => 'set_terms',
        'insert_comment' => 'insert_comment',
        'get_post_meta' => 'get_post_meta',
        'get_total_ezine_post' => 'get_total_ezine_post',
        'get_next_time_to_post' => 'get_next_time_to_post',
        'cancel_scheduled_post' => 'cancel_scheduled_post',
        'serverInformation' => 'serverInformation',
        'maintenance_site' => 'maintenance_site',
        'keyword_links_action' => 'keyword_links_action',
        'branding_child_plugin' => 'branding_child_plugin',
        'code_snippet' => 'code_snippet',
        'uploader_action' => 'uploader_action',
        'wordpress_seo' => 'wordpress_seo',
        'client_report' => 'client_report',
        'createBackupPoll' => 'backupPoll',
        'page_speed' => 'page_speed',
        'woo_com_status' => 'woo_com_status',
        'heatmaps' => 'heatmaps',
        'links_checker' => 'links_checker',
        'wordfence' => 'wordfence',
        'delete_backup' => 'delete_backup',
        'update_values' => 'update_values',
        'ithemes' => 'ithemes',        
        'updraftplus' => 'updraftplus',
        'backup_wp' => 'backup_wp'
    );






