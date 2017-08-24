Yii2 Advanced Application Template (Fixed Bower version)
=====================================================

Yii 2 Advanced Application Template with Fixed Bower

[![Latest Stable Version](https://poser.pugx.org/yidas/yii2-app-advanced/v/stable?format=flat-square)](https://packagist.org/packages/yidas/yii2-app-advanced)
[![Latest Unstable Version](https://poser.pugx.org/yidas/yii2-app-advanced/v/unstable?format=flat-square)](https://packagist.org/packages/yidas/yii2-app-advanced)
[![License](https://poser.pugx.org/yidas/yii2-app-advanced/license?format=flat-square)](https://packagist.org/packages/yidas/yii2-app-advanced)

Let you use pure Composer to install or update Yii2 smoothly, even no more setting by puting it on Git to co-work with team. 

---

INTRODUCTION
------------

This template is a branch of [Yii 2](http://www.yiiframework.com/) advanced application, which includes Bower vendor already and requires [yidas/yii2-composer-bower-skip](https://github.com/yidas/yii2-composer-bower-skip) for updating composer smoothly without Bower. Further, the `.gitignore` is set already for excepting bower, so that share the project on Git for teamwork will not need to set more, each projects by Git clone also include fixed Bower already.  

In this template, Bower packages are fixed for current version relating to Yii2 core, so you need to manually update Bower-Asset when needed.

---

INSTALLATION
------------

### Install via Composer

If you do not have [Composer](http://getcomposer.org/), you may install it by following the instructions
at [getcomposer.org](http://getcomposer.org/doc/00-intro.md#installation-nix).

You can then install this project template using the following command:

```
composer create-project --prefer-dist yidas/yii2-app-advanced
```

Also, you can make a minimal installation without development tool:
```
composer create-project --prefer-dist --no-dev yidas/yii2-app-advanced
```

> With --no-dev project, set to prod-env or remove the debug & gii usage from `config/web.php` to prevent error.

---

### Install from an Archive File

[Download yii2-app-advanced-2.0.12 Archive](https://github.com/yidas/yii2-app-advanced/releases/download/2.0.12/yii2-app-advanced-2.0.12.tar.gz)

Extract the downloaded file to a  Web-accessible folder, which includes vendor already.

---

DOCUMENTATION
-------------

Please refer to [Yii 2 Advanced Project Template Document](https://github.com/yiisoft/yii2-app-advanced/blob/master/docs/guide/README.md)
