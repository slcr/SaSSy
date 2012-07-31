SASS Basic Project
=============

Basis Sheet für Projekte mit SASS/SCSS Erweiterung.

Benutzung:
------------

Ordner überwachen mit Compass:  
  `compass watch /path/to/myProject`  

Es werden folgende Scripte geladen:


### SASS Partials

    @import "compass";
    
    // First of all, load the Variables 
    @import "partials/variable";
    
    // RESET ALL THE THINGS! .o/ 
    @import "partials/reset";
    
    // Clearfix 'n stuff 
    @import "partials/hacks";
    
    // Some Mixins to completely lose yourself… 
    @import "partials/mixins";
    
    // Animations to work with 
    @import "partials/animations";
    
    // Form Styles, from labels to input over textareas 
    @import "partials/forms";
    
    // import some font-awesome with a lot of icons to get along with 
    @import "partials/font-awesome";
    
    // some media queries with custom breakpoints and mixins 
    @import "partials/media-queries";
    
    // a grid that still needs some love 
    @import "partials/grid";
    
    // all the headlines and paragraphs you love 
    @import "partials/typography";
    
    // --- IF USING WORDPRESS ------------------------------------------------- 
    //@import "partials/wordpress"
     
    // ------------------------------------------------------------------------ 
     
    // Basic Declarations, all content goes here 
    @import "partials/base";
  
  
### Konfiguration

    project_type = :stand_alone 
     
    # paths 
    http_path       = "/" 
    css_dir         = "/" 
    sass_dir        = "sass" 
    images_dir      = "img" 
    javascripts_dir = "js" 
     
    # output option: nested, expanded, compact, compressed 
    output_style = :compact 
    
    # Use :development to see line numbers, file names, etc 
    environment = :production 
     
    # To disable debugging comments that display the original location of your selectors. Uncomment: 
    line_comments = false 
     
    # To enable relative paths to assets via compass helper functions. Uncomment: 
    relative_assets = true 
     
    # disable the asset cache buster 
    asset_cache_buster :none