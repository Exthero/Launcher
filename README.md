# 2009scape Launcher

The official launcher for 2009scape/2009scape-compatible sources

# Running

1. Start the 2009scape Management Server & Server on localhost (found [here](https://github.com/2009scape/2009scape))
2. Run `src/com/fox/Launcher.java`

Note: To be able to download client and cache through the launcher you need to have a web server running and you need to have the cache + client jar in the web root of the web server.

## Troubleshooting

* No audio (Linux)
  * Install Pipewire (and Pipewire-alsa) as a replacement to Pulseaudio. This is a deep Java issue that will hopefully disappear with Pulseaudio's phasing out over the 2021/2022
