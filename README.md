BreadcrumbHelper
================

create breadcrumb in view file (CakePhp)

1. Go to the folder app/View/Helper and create a file name BreadcrumbHelper.php
2. Use the file BreadcrumbHelper.php
3. Add this helper to controller where you want to use.
4. var $helpers = array(‘Breadcrumb’);
5. you can use this helper in your view file.
6. echo $this->Breadcrumb->create(array(
            array(
              ‘title’ => ‘Home’,
              ‘url’ => array(‘controller’ => ‘some_controller’,'action’ => ‘some_action’),
              ‘class’ => ”
            ),
            array(
              ‘title’ => ‘Listing Paeg’,
              ‘url’ => array(‘controller’ => ‘some_controller’,'action’ => ‘some_action’,'some_parameters_if_needed’),
              ‘class’ => ‘current’
            ),
            array(
              //more links
            )
    ));

