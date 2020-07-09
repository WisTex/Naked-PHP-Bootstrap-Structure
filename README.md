# Naked-PHP-Bootstrap-Structure
Basic file and directory structure designed to help you convert HTML based templates to PHP.

## Purpose of this Code
You can use this code in two ways:

1. To take an existing HTML based template and reassemble it into a PHP / MySQL file structure.
2. To use as a base for an HTML template you are creating so that can easily be used with PHP / MySQL.

This repository contains the empty files and folder structure, plus instructions on how to convert the HTML template into PHP. It does not work out of the box and is not intended to. It's just here to save you some time.

## What You Will Need

1. This set of naked files.
2. An HTML based template you want to convert.
3. Code you wish to use to connect to the database.
4. A basic understanding of HTML, PHP, Javascript, MySQL and copy and pasting.

Additionally, you may also need:

5. To download the latest versions of Bootstrap, JQuery or other libraries, if your template uses them, or you intend on using them.
6. The code necessary to connect with your login or user management system.

For example, your HTML template may come with a copy of Bootstrap, but it is not the most secure version. You would want to update it. But make sure that you update to the same major version of Bootstrap. Update version 3.x to the latest version of 3, or update version 4 to the latest version of 4. Version 4 is not backwards compatible with 3.

Or, another example, is if you have a script that handles user sessions. You would want to integrate the appropriate code into your pages so that it works. This would be different for each user management system.

## Important Notes
Here are some things to keep in mind:

If the HTML template you are converting expects certain things in certain places, you might have to change the structure a bit. For example, if it expects Bootstrap to be in a certain directory, you either need to put it in that directory, or change all references to point to the new location.

You can also use a CDN for Bootstrap, jQuery and other popular libraries. There are upsides and downsides to doing this. We like using a local copy, so we can ensure availability, but you can link to the CDN version instead if you want.

There may be things included in this structure that you do not use. You don't have to use it. For example, if you do not have a user login system, then you can remove the code that reference that.

## Comments in the Code
We have tried to comment the code as much as possible so that you can quickly figure out what does what, and any developers who have to maintain your code after you will know what the basic structure of the site is.

We have left some spots where you can fill in the blank with additional information. These are obviously optional, but we've found that having certain notes helps us when we go back to edit code we've long forgotten about. It might save you time down the road if you add your own comments.

Some useful things you might want to fill out in the comments:
* If it is a template you created, add the link to your website in the approproate spots.
* If you are using someone else's HTML template, include a link to the documentation for the template, either locally or online.
* If you have your own repository, you may want to link to it, as well.

## Why
When I am creating a new website from sratch, I frequently use a custom template, and these templates are often made by third parties and mostly consist of HTML. Since I am making a PHP based database driven website, I have to convert their HTML template into usable PHP files.

To make it easier to convert the HTML template into PHP files, I have created this basic structure to speed up the process.

I figured that I am not the only one with this task, so I am sharing the code here for everyone to use.

## License & Uses
This code is licensed under the MIT license. So you basically can do what you want with it as long as you give us credit and include a copy of the MIT license for our code. We politely ask that you leave links to the main repsoitory in the source code, both for your future reference, and because, well, we like getting credit for our little part of the code.

You can use it for:
1. Creating your own websites.
2. Incorporating this into a template you are creating.
3. Using it as class exercises on how to convert HTML websites to PHP.

If you do use this code in combination with script licensed under a GPL or similar license, or any license that is more restrictive than the MIT license, we kindly ask you to leave the link to the MIT version of this code (our main repository) so if people want JUST this code, they can still get it under the MIT license.

The main repository for this code resides at: https://github.com/WisTex/Naked-PHP-Bootstrap-Structure
