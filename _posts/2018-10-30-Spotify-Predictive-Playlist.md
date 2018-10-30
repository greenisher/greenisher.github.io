---
layout: post
title:  "Spotify Predictive Playlist"
date:   2018-10-30 01:27:41 +0000
categories: Python
---
I really like music, but I can tend to deep dive into music I already like while neglecting new releases. I'm also interested in APIs and machine learning.

Spotify has one of the best APIs ever. It analyses each song for things like beat, tempo and valence, and produces recommendations for you based on that.

I built my [analysis][analysis-nb] using machine learning techniques, pulling in music I liked from a playlist and determining the music I enjoyed and then iterating over music to determine how likely I would be to enjoy it. It then pushes that music straight to a separate [playlist][my-playlist] of songs I am likely to enjoy.

This is a work in progress. Future editions will run from the command line and iterate over current releases instead of just one playlist.



[analysis-nb]: https://github.com/greenisher/PredictivePlaylist
[my-playlist]: https://open.spotify.com/playlist/3Of013LqtgztO2zmo0ovGn