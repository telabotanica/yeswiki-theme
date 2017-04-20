# yeswiki-theme

Ce contenu est à placer dans le dossier `themes/telabotanica/` (prioritaire) ou dans `tools/templates/themes/telabotanica/` de YesWiki.
Il faut adapter la configuration du theme dans `wakka.config.php` :

```php
$wakkaconfig = array(
  ...
  'favorite_theme' => 'telabotanica', // doit correspondra au nom du dossier ci-dessus
  'favorite_style' => 'telabotanica.css',
  'favorite_squelette' => '2cols-left-tb.tpl.html',
  ...
);
```
