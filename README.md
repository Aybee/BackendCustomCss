Contao Extension: BackendCustomCss
==================================

Provides the possibility to add special css to the contao backend.

There are 3 types of custom css:
- templates ... delivered by this extension (send me yours, if you want to put it in this collection)
- system styles ... added by system admin to settings (could be marked `fix` ... will always be used, even if usage custom css is not activated by user)
- user styles ... each user could set its own styles in user settings

The system styles (defined by admin) will automatically be listed in user settings (if active) and described in the wizard. Each style could be set inactive (will not be loaded).

Each user style can also be set to inactive (must not be deleted in order to avoid loading).


Installation
------------

The extension is not published in contao extension repository.
Install it manually or via [composer](https://packagist.org/packages/cliffparnitzky/backend-custom-css).


Tracker
-------

https://github.com/cliffparnitzky/BackendCustomCss/issues


Compatibility
-------------

- min. version: Contao 2.9.5
- max. version: Contao 3.2.x


Dependency
----------

- This extension is dependent on the following extensions: [[MultiColumnWizard]](https://contao.org/en/extension-list/view/MultiColumnWizard.html), [[TechnicalValueRegex]](https://github.com/cliffparnitzky/TechnicalValueRegex)


Screenshots
-----------

![Screenshot: System settings](https://raw.github.com/cliffparnitzky/BackendCustomCss/master/screenshot_settings.jpg)

![Screenshot: User settings](https://raw.github.com/cliffparnitzky/BackendCustomCss/master/screenshot_user.jpg)

![Screenshot: Wizard for templates](https://raw.github.com/cliffparnitzky/BackendCustomCss/master/screenshot_user_wizard_templates.jpg)

![Screenshot: Wizard for system styles](https://raw.github.com/cliffparnitzky/BackendCustomCss/master/screenshot_user_wizard_system_styles.jpg)