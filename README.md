# Description

Home Assistant blueprints for media player control using an input boolean

# Motivation

Latest version of [Home Assistant Mater Hub](https://github.com/t0bst4r/home-assistant-matter-hub) changed the way media players are exposed to matter controllers. They are now exposed as speakers, which is not compatible with some matter controllers (Alexa for instance). [v3.0.0-alpha.83 release notes](https://github.com/t0bst4r/home-assistant-matter-hub/releases/tag/v3.0.0-alpha.83) advise to use and expose an input_boolean to control on / off state of media players using such controllers. Here are some blueprints created to facilitate the 2-way sync between the media_player entity and the input_boolean entity needed for this to work. You can then expose the input_boolean to you matter controller in order for it to control on / off state of a media_player.

# Usage

- import both blueprints in home assistant
- Configure each blueprint
  - select a media_player entity
  - select an input_boolean entity
  - save
