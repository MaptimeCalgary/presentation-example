# ExamplePresentation
Just an example of presentation.

## Instructions

To copy this template presentation into your Github account so that you can make it your own:

1. [Create an empty repo](https://github.com/new) on Github _(ex. `presentation-your-topic`)_
2. After creating the repository, you can choose to `Import code`: ![Import code button](https://cloud.githubusercontent.com/assets/897290/7187563/a3637a08-e42e-11e4-874e-ae9845224445.png)
3. On the Github Importer page, enter in the link to this repository (`https://github.com/MaptimeCalgary/presentation-example`): ![screenshot from 2015-04-16 11 51 37](https://cloud.githubusercontent.com/assets/897290/7187614/f6f89cde-e42e-11e4-94d0-4d92d5a4c6ef.png)
4. Press "Begin import" and (after a few seconds) you'll be taken to your new presentation. Go ahead and start making edits!
5. Your presentation should be available under `http://your-username.github.io/presentation-your-topic`

## Customizing Slide Style

From the repo base, fire up a [Sass](http://sass-lang.com/) compiler:
```bash
sass theme/source/maptimecalgary.scss:theme/maptimecalgary.css --watch
```
Now edit the theme style at `theme/source/maptimecalgary.scss`

## FAQ

> Why clone the repo rather than fork the repo?

The problem with forking is that, on Github, you can only have one fork of a repo on your account (unless you email Github and ask them to disassociate the fork with the source). This means that if you want to have multiple presentations on your account that are based off of this presentation example, you'll be disappointed.
