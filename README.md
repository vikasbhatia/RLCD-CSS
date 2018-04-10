<h1 align="center">RLCustomDesigns CSS</h1>

<p align="center">
CSS theme for <a href="https://reddit.com/r/RLCustomDesigns">r/RLCustomDesigns</a>.
</p>

<p align="center">
<img src="https://forthebadge.com/images/badges/built-with-love.svg" alt="Built with ♥">   
</p>

<h4 align="center">
  <a href="#features">Features</a> •
  <a href="#getting-started">Getting Started</a> •
  <a href="#usage">Usage</a> •
  <a href="#references">References</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#known-limitations">Known Limitations</a> •
  <a href="#acknowledgements">Acknowledgements</a>
</h4>

## Features

Based on Naut (see [r/Naut](reddit.com/r/Naut) for more details).

* Dark mode.
* Subreddit link in the logo.
* Rocket League quick chat upvote animation.

[<sub><sup>Back to top</sup></sub>](#rlcustomdesigns-css)

## Getting Started

### Installing

You must be a moderator to be able to edit CSS.

1. Go to `reddit.com/r/RLCustomDesigns/about/stylesheet`.
2. Upload all the images in the `images` folder. Make sure the names are unchanged.
3. Copy the contents of `style.css` into the space there.
4. Save.

### Setting up Flairs

1. Go to `reddit.com/r/RLCustomDesigns/about/flair`.
2. Add the user you want to grant a flair to and give them a CSS class.
3. Add the following snippet to the CSS in the addons section:

```
.flair.flair-<name> {
    background: #1f1f1f;
    border: #1f1f1f;
    color: #<colour>;
}
```
Where `<name>` is the name you gave your class in step 2, and `<colour>` is the colour of the text you want. Example:

 <p align="center">
<img width="350" alt="Edit Flair" src="https://user-images.githubusercontent.com/11446387/38540192-bc29284a-3cb8-11e8-91f2-e92a410c055b.png">
</p>

<p align="center">
<img width="184" alt="Text Flair CSS Classes" src="https://user-images.githubusercontent.com/11446387/38539681-c819d106-3cb6-11e8-87f7-cdac32fab495.png">
</p>


[<sub><sup>Back to top</sup></sub>](#rlcustomdesigns-css)

## References

* [r/Naut](https://www.reddit.com/r/naut/)
* [Dead Pixel](https://www.reddit.com/r/csshelp/comments/3113sm/what_is_the_best_april_fools_prank_for_css/cpxp1np/)

## Contributing

Pull requests are welcome. If you've got ideas or feature requests, please feel free to create an issue on this repo.

## Known Limitations

* For a logged-out user, the login form on the sidebar doesn't work since the margin makes it overlap with the "Submissions restricted" text above it. If this margin is increased to prevent the overlap, the form looks awkward on other logged-out pages.


## Acknowledgments

* **u/GetSchwiftyClub** for help with testing.
* **u/DBaum1** for help with testing.

**Last Updated: 10 April 2018**