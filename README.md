# plushu-buildstep-buildpacks

Installs the set of custom buildpacks originally included in [buildstep][]
that have since been removed:

  * Metorite - `https://github.com/oortcloud/heroku-buildpack-meteorite.git`
  * Perl - `https://github.com/miyagawa/heroku-buildpack-perl.git`
  * Dart - `https://github.com/igrigorik/heroku-buildpack-dart.git`
  * NGINX - `https://github.com/rhy-jot/buildpack-nginx.git`
  * Apache - `https://github.com/Kloadut/heroku-buildpack-static-apache.git`
  * Jekyll - `https://github.com/bacongobbler/heroku-buildpack-jekyll.git`

[buildstep]: https://github.com/progrium/buildstep/

## Usage

```bash
# if you haven't already installed the buildpacks plugin
plushu install buildpacks

# you may want to install the buildpacks that are still part of buildstep:
# plushu install buildstep-buildpacks

plushu install buildstep-custom-buildpacks
```
