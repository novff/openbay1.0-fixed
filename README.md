openbay
=======
this is a fork of the old version of openbay aimed at patchinf it up and making it run on modern servers and hostings



is the open source clone of the piratebay created by the team that brought you [isoHunt](https://isohunt.to) and [oldpiratebay.org](http://oldpiratebay.org).




Installation
=======

**Step 1. download the source code.**

**Step 2. Upload source code to your web host.**

Upload the source code to your host using the hosting guide
(in common case there is a CPanel tool) or just use FTP

**Step 2.1. Unzip source to hosting folder (optional)**

Some hosts can unzip sources automatically, others require you to do it manually.

**Step 4. Set hosting environment (optional)**

*Apache*

This option **is available by default** in original source pack. You can see it
at `conf/example.htaccess`

*Nginx*

This config is available in original source pack at `/conf/example.nginx.conf`

*Sphinx* (**advanced mode**)

[Instruction here](https://github.com/isohuntto/openbay/wiki/sphinx)

*MySQL* (**advanced mode**)

Before the wizard will run you need to create a database, the wizard will create
the schema. The dump is at `/src/protected/data/schema.mysql.sql`

**Step 5. Wizard**

Open your website and follow the guide provided there. By default, you will need
to put a title which will appear on all the site's pages.

[Detailed instruction here](https://github.com/isohuntto/openbay/wiki/shared-hosting-guide)

How to contribute?
==================

Report issues, submit pull requests to fix problems, or to create summarized and
documented feature requests (preferably with code that implements the
feature).

**Feel free to contribute to the project in any way you like!**
