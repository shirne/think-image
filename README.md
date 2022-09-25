# The ThinkPHP5 Image Package

[![Build Status](https://img.shields.io/travis/shirne/think-image.svg)](https://travis-ci.org/shirne/think-image)
[![Coverage Status](https://img.shields.io/codecov/c/github/shirne/think-image.svg)](https://codecov.io/github/shirne/think-image)
[![Downloads](https://img.shields.io/github/downloads/shirne/think-image/total.svg)](https://github.com/shirne/think-image/releases)
[![Releases](https://img.shields.io/github/release/shirne/think-image.svg)](https://github.com/shirne/think-image/releases/latest)
[![Releases Downloads](https://img.shields.io/github/downloads/shirne/think-image/latest/total.svg)](https://github.com/shirne/think-image/releases/latest)
[![Packagist Status](https://img.shields.io/packagist/v/shirne/think-image.svg)](https://packagist.org/packages/shirne/think-image)
[![Packagist Downloads](https://img.shields.io/packagist/dt/shirne/think-image.svg)](https://packagist.org/packages/shirne/think-image)

## 安装

> composer require shirne/think-image

## 使用

~~~
$image = \think\Image::open('./image.jpg');
或者
$image = \think\Image::open(request()->file('image'));


$image->crop(...)
    ->thumb(...)
    ->water(...)
    ->text(....)
    ->save(..);

~~~
