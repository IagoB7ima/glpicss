## GLPI-UNISUAM

# Arquivos e pastas do GLPI que foram modificadas

* css/includes/_base.scss

    linha 91
    .page {
        .glpi-logo {
            background: url($logo) no-repeat;
            height: 55px;
            width: 160px;
        }
     }   
        
    .page-anonymous {
        .glpi-logo {
            width: 0px;
            height:0px;
        }
    }  
        
* css/includes/logo_.scss

$logo-light: "../pics/logos/logo-unisuam-branco-150.png" !default;
$logo-light-reduced: "../pics/logos/logo-G-unisuam-branco-100.png" !default;
$logo-dark: "../pics/logos/logo-GLPI-100-black.png" !default;
//$logo-dark-reduced: "../pics/logos/logo-G-100-black.png" !default;
$logo-dark-login: "../pics/logos/logo_unisuam_vertical.png" !default;
$logo-light-login: "../pics/logos/logo_unisuam_vertical.png" !default;
$logo: $logo-light;
$logo_reduced: $logo-light-reduced;
