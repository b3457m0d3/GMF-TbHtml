# GMF-TbHtml
a modified version of the TbHtml Helper class from Yii-Bootstrap (or Yiistrap)

### Usage
``` php
  $this->widget('bootstrap.widgets.TbHeroUnit', array(
		'heading' => 'Hello, world!',
		'content' => '<p>This is a simple hero unit, a simple jumbotron-style component for calling extra attention to featured content or information.</p>' . TbHtml::button('Learn more', array('color' =>TbHtml::BUTTON_COLOR_PRIMARY, 'size' => TbHtml::BUTTON_SIZE_LARGE)),
	));
	$this->widget('bootstrap.widgets.TbNavbar', array(
		'brandLabel' => 'Title',
		'display' => null, // default is static to top
		'items' => array(
			array(
				'class' => 'bootstrap.widgets.TbNav',
				'type'  => TbHtml::NAV_TYPE_NAVBAR, // this is necessary for the navbar to render properly
				'items' => array(
					array('label' => 'Home', 'url' => '#', 'active' => true),
					array('label' => 'Link', 'url' => '#'),
					array('label' => 'Link', 'url' => '#'),
				),
			),
		),
	));
```
