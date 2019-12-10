---
title: Getting Started
description: Getting started with Deployer.
extends: _layouts.documentation
section: content
---

# Getting Started {#getting-started}

## Requirements
Your project must be a `git repository` and the system where `deployer` is fired must contain `git` in the `$PATH`.


## Installation {#installation}
Deployer has been designed to work in any PHP project.

<div class="bg-blue-500 p-4 rounded shadow text-gray-100">
    <h1 class="text-xl text-gray-100">Laravel users</h1>
    <div class="text-sm">
        If you are developing a Laravel project, a Laravel integration package is available. Please follow the 
        <a href="#laravel-installation" class="text-blue-800">next section</a> instead.
    </div>
</div>

You can install deployer into your project with:

```
composer require kodilab/deployer dev-master
```

### Laravel installation {#laravel-installation}
If your project is based on `Laravel framework`, then you can use the `laravel-deployer` package which includes
some integrations with `Laravel`:

* The deployer configuration is integrated with Laravel's configuration system.
* Includes an `artisan command` to start a deploy

To install deployer & the laravel integration:

```
composer require kodilab/laravel-deployer dev-master
```

