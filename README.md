# Vaa-guide

Guide for application managers using the OpenVAA voting advice application framework

## To do

* i18n: https://github.com/untra/polyglot
* Aling styling with the VAA: https://mzrn.sh/2022/04/09/starting-a-blank-jekyll-site-with-tailwind-css-in-2022/

## Deployment

Just push to Github.

## Editing the Theme

Mainly edit `docs/assets/main.scss`.

See: https://github.com/jekyll/minima/tree/v2.5.1

## Local Testing

Run:

    cd docs
    bundle install
    bundle exec jekyll serve

Go to: http://localhost:4000

If you make changes to `/docs/_config.yml`, rerun the command for updates to take effect.

## Troubleshooting Ruby

If `bundle install` fails due to HTTPErrors, try disabling IPv6 resolution: [Linux](https://stackoverflow.com/questions/49800432/gem-cannot-access-rubygems-org/50349235#50349235), [MacOS](https://stackoverflow.com/a/51015358).