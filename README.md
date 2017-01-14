# gerpy

A tool to draw spam pictures at GitHub activity charts with fake commits. Sorry for that!

Inspired by [sijeko's](https://github.com/sijeko) [gerda](https://github.com/sijeko/gerda)

# Disclaimer

Author feels really guilty for providing a tool that possibly could inspire someone to spam GitHub with fake commits. Every byte here is filled with this heavy burden sense.

Please don't ever forget that hammer is a tool to nail nails, and not to hit your buddy in a face.

On other hand, GitHub probably suffers much more scaled attacks, so a little joke program could be acceptable.

Despite distributing under kinda free license, author still kindly remind you of your responsibility and asks not to do shit. :)

# Usage

Clone the repo, edit the map and draw things!

```
# Preparations
sudo apt install python pyton-yaml  # 2.7

# Obvious things
git clone git@github.com:agrrh/gerpy.git
cd gerpy

# See Ma, I'm an artist!
cp maps/{example,my}.gerpymap
${EDITOR} maps/my.gerpymap

# Run the things
./gerpy maps/my.gerpymap
```

# Palette

Palettes are stored in YAML files.

See `./palettes/` folder.

# License

WTFPL, of course
