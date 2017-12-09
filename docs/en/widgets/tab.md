# Tab component

The `Core\Admin\Widgets\Tab` class is used to generate the tab components:

```php
use Core\Admin\Widgets\Tab;

$tab = new Tab();

$tab->add('Pie', $pie);
$tab->add('Table', new Table());
$tab->add('Text', 'blablablabla....');

echo $tab->render();

```

The `Tab::ad ($title, $content)` method is used to add a tab, `$title` for the option title, and the` $content` tab for the content.