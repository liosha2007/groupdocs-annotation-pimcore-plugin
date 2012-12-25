## GroupDocs Annotation Plugin for PimCore CMS.

For use plugin add code to your view:
```php
<?php $groupDocs = new GroupDocsAnnotation_GroupDocs(); ?>
<?php echo $groupDocs->renderFrame(); ?>
```

#### For configure default params login as admin and go to "Extras" => "Configure GroupDocs Annotation"  menu.

Also you can override default params like:
```php
<?php $groupDocs1 = new GroupDocsAnnotation_GroupDocs(array( 'fileid' => '123', 'frameborder' => '1', 'width' => '680', 'height' => '900' )); ?>
<?php echo $groupDocs1->renderFrame(); ?>
```
