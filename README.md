# ExamplePresentation
Just an example of presentation.

## Instructions

To use this as a base for a presentation, follow the steps outlined in the [Duplicating A Repository](https://help.github.com/articles/duplicating-a-repository/):

1. [Create an empty repo](https://github.com/new) on Github _(ex. `presentation-your-topic`)_
1. Clone this `presentation-example` repo locally: `git clone https://github.com/MaptimeCalgary/presentation-example.git presentation-your-topic`
1. Change directory to local clone: `cd presentation-your-topic`
1. Set your new empty repo as the remote: `git remote set-url origin git@github.com:your-username/presentation-your-topic`
1. Push code: `git push`
1. Your presentation should be available under `http://your-username.github.io/presentation-your-topic`
1. Edit code!

## Customizing Slide Style

From the repo base, fire up a [Sass](http://sass-lang.com/) compiler:
```bash
sass theme/source/maptimecalgary.scss:theme/maptimecalgary.css --watch
```
Now edit the theme style at `theme/source/maptimecalgary.scss`

## FAQ

> Why clone the repo rather than fork the repo?

The problem with forking is that, on Github, you can only have one fork of a repo on your account (unless you email Github and ask them to disassociate the fork with the source). This means that if you want to have multiple presentations on your account that are based off of this presentation example, you'll be disappointed.
