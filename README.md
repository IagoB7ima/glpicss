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
          
        
* css/includes/logo_.scss

    $logo-light: "../pics/logos/logo-unisuam-branco-150.png" !default;

    $logo-light-reduced: "../pics/logos/logo-G-unisuam-branco-100.png" !default;

    $logo-dark: "../pics/logos/logo-GLPI-100-black.png" !default;

    //$logo-dark-reduced: "../pics/logos/logo-G-100-black.png" !default;

    $logo-dark-login: "../pics/logos/logo_unisuam_vertical.png" !default;

    $logo-light-login: "../pics/logos/logo_unisuam_vertical.png" !default;

    $logo: $logo-light;

    $logo_reduced: $logo-light-reduced;

* css/lib/tabler/core/src/scss/ui/_login.scss

    .welcome-anonymous{
        .container-tight{
            width: auto;
            .card {
                width: 400px;
            }
        }
        .col-md-5{
            width:100%
        }
        background-image: url("../pics/logos/fundo.png");
        background-repeat: no-repeat;
        background-position: center;
        height: 100%;
    }
    
* pics/logos

* pics/favicon.ico
