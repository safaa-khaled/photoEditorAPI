<p align="center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>


## About Photo Editor Api

Photo Editor API that allows the user to perform many operations on a given image, this image can be a file from the computer or URL from the Internet. 
The available operations are: image cropping, resizing, rotating, flipping, inverting color, and changing contrast and brightness. Each process has parameters defined in the postman request.

to run photo editor api on your machine:
- download repository zip file to your machine and extract it.
- copy .env file.
- in terminal or cmd run this instructions:
    - composer update
    - php artisan key:generate
    - php artisan serve
- test photo editor api in postman using photoEditorApi.postman_collection.json which could be found in photoeditorapi zip file.