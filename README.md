# Octopress Last.fm Aside

This is a simple aside for [Octopress](http://www.octopress.org) that uses Last.fm API to pull your most recently listened tracks from your account.

It was greatly inspired by [Octopress Flickr Aside](https://github.com/amelandri/Octopress-Flickr-Aside) that inserts Flickr photos in the sidebar.

## How to use it

First of all you need to copy *lastfm.html* into your octopress installation in the directory *source/_includes/custom/asides*.
Then you need to update the _config.yml file:

* add *'custom/asides/lastfm.html'* to *default_asides*
* add lastfm settings at the end of the file:

```
#Last.fm
lastfm_apikey: <your lastfm api_key>
lastfm_user: <your lastfm username>
lastfm_count: <# of tracks to be displayed/retrieved>
```

Read about the Last.fm API [here](http://www.last.fm/api/intro) and get an API key [here](http://www.last.fm/api/account).

Please feel free to fork and contribute.

Enjoy!