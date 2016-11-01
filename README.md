#Teraquant

<div class="span12">
  		<div class="well">
  			<h2 id="existing_install">
  				Installation for existing sites</h2>
  			<p>Extract the downloaded theme.</p>
  			<p>Folders <b>modules</b> contain all described below modules.</p>
  			<p>&nbsp;</p>
  			<p>The list of <b>required</b> modules:</p>
        <ol>
          <li>
            <b><a href="https://drupal.org/project/ctools" target="_blank">ctools</a></b> - Chaos tools (required by many modules).</li>
          <li>
            <b><a href="https://drupal.org/project/link" target="_blank">link</a></b> - Link CCK fields.</li>
          <li>
            <b><a href="https://drupal.org/project/shortcode" target="_blank">shortcode</a></b> - Shortcode integration.</li>
          <li>
            <b><a href="https://drupal.org/project/token" target="_blank">token</a></b> - Token module (required by Pathauto).</li>
          <li>
            <b><a href="https://drupal.org/project/views" target="_blank">views</a></b> - Views module.</li>            
          <li>
            <b><a href="https://drupal.org/project/media" target="_blank">media</a></b> - Media widget for Image field.</li>
          <li>
            <b><a href="https://drupal.org/project/date" target="_blank">date</a></b> - Date field for nodes.</li>
          <li>
            <b><a href="https://drupal.org/project/file_entity" target="_blank">file_entity</a></b> - File Entity is required by Media module.</li>
          <li>
            <b><a href="https://drupal.org/project/jquery_update" target="_blank">jquery_update</a></b> - jQuery Update.</li>
          <li>
            <b><a href="https://drupal.org/project/shortcode" target="_blank">shortcode</a></b> - Dynamic Properties.</li>
         </ol>
  			<p>&nbsp;</p>
  			<p>The list of <b>optional</b> modules which are integrated in this theme:</p>
  			<ol>
          
  				<li>
  					<b><a href="https://drupal.org/project/admin_menu" target="_blank">admin_menu</a></b> - Usefull administrion menu</li>
          <li>
            <b><a href="https://drupal.org/project/pathauto" target="_blank">pathauto</a></b> - Pathauto (SEO friendly URLs).</li>
          <li>
            <b><a href="https://drupal.org/project/retina_images" target="_blank">retina_images</a></b> - Retina Images, high resolution images for retina displays</li>
          <li>
            <b><a href="https://drupal.org/project/ckeditor" target="_blank">ckeditor</a></b> - CKEditor is a WYSIWYG editor.</li>
          <li>
            <b><a href="https://drupal.org/project/libraries" target="_blank">libraries</a></b> - Libraries (required by CKEditor).</li>
          <li>
            <b><a href="https://drupal.org/project/tb_megamenu" target="_blank">tb_megamenu</a></b> - Mega Menu.</li>
  			</ol>
        <p>&nbsp;</p>
        <p>The list of <b>core</b> modules which are used:</p>
        <ol>
          <li>
            <b>block</b> - Block</li>
          <li>
            <b>comment</b> - Comments</li>
          <li>
            <b>search</b> - Search Form</li>
        </ol>        
        <p>&nbsp;</p>
        <p>The list of modules for importing content:</p>
        <ol>
          <li>
            <b><a href="https://drupal.org/project/features" target="_blank">features</a></b> - Features (Importing Teraquant theme features).</li>
          <li>
            <b><a href="https://drupal.org/project/blockexport">blockexport</a></b> - Block Export Feature</li>
          <li>
            <b><a href="https://drupal.org/project/node_export">node_export</a></b> - Node Export Feature</li>
          <li>
            <b><a href="https://drupal.org/project/uuid">uuid</a></b> - UUID required for Node Export</li>
        </ol>   
  			<h4>
  				Upload files:</h4>
  			<ol>
  				<li>
  					Upload from <b>themes</b> to your site folder in <b>/sites/all/themes</b></li>
  				<li>
  					Upload from <b>modules</b> all required modules to your site in <b>/sites/all/modules</b> folder.</li>
          <li>
            Upload from <b>libraries</b> all libraries to your site in <b>/sites/all/libraries</b> folder.</li>
          <li>
            Upload from <b>files</b> all in <b>/sites/default/files</b> folder.</li>
  			</ol>
        <p>Go to <b>Configuration/Media/File system</b> and rewrite your Public file system path to <code>sites/default/files</code></p>
        <p>Go to the Modules page <b>admin/modules</b> and enable all required modules described above.</p>
        <p>Please make sure what you are have enabled next modules before enabling the theme:
        </p><ul>
          <li>
            Rhythm theme module.</li>
          <li>
            Rhythm Shortcodes.</li>
          <li>
            NikaDevs Visual Shortcodes.</li>
          <li>
            NikaDevs Main Functions.</li>
        </ul>
  			<p>Login to your Drupal site and go to <b>admin/appearance</b> enable the <b>Teraquant Sub Theme</b> theme and set it as the default theme.</p>
        <p>Go to jQuery Update page <b>admin/config/development/jquery_update</b> and set the Default jQuery Version to 1.10 and version 1.8 for Administration pages.</p>
      </div>
