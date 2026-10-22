# 2Balance

The website for 2balance.network. 2Balance is a daily practice of tending to yourself across six needs: connect, create, eat and drink, move, play, rest.

## How it is built

- Plain HTML pages with no build step, served by GitHub Pages.
- The top bar and sign-in load from https://2gather.network/nav/ with no version number. That host answers with `cache-control: no-cache`, so a change there reaches every site.
- The look follows 2Gather. The top bar shows 2Balance's own logo on this host.
