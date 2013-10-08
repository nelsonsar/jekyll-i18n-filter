Jekyll i18n Filter
==================

**IMPORTANT**

I'm not the creator of this code. This code was originally create by [@gacha](https://github.com/gacha/).
I just put it in a repository to be easy to clone. I don't wanna to steal nothing
from anyone. Just make easier for more folks like me to use it.

The link for the original file is at [gacha's repo](https://github.com/gacha/gacha.id.lv/blob/master/_plugins/i18n_filter.rb).

Thanks [@gacha](https://github.com/gacha/)!

Jekyll i18n Filter is an option for localization in your [Jekyll](http://jekyllrb.com) blog.

The setup
=========

To start localize things is easy.

Just copy ```i18n_filter.rb``` file to your plugins directory.

After copy it you'll need to change ```LOCALE``` to your desired locale like, for example, ```pt-BR```.

To use localize you'll need to download from [rails-i18n](https://github.com/svenfuchs/rails-i18n/tree/master/rails/locale)
the locale that you put in ```LOCALE``` and put it in ```_locales``` folder.

How to use
==========

You can use localize in Jekyll variables like post date. Example:

```{{ post.date | localize: "%d/%m/%Y" }}```

Eaaaaasy as get drunk!
