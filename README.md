# stylegun
Living la vida Style Tiles

## Set up

If you've never used git before, open a command line interface (Terminal, iTerm, etc), type in

``sudo git``

and then follow instructions from the prompt.

If you have never set up any development tools, check out this blog post or grab a developer wandering nearby. [http://burnedpixel.com/blog/beginners-setup-guide-for-ruby-node-git-github-on-your-mac/](http://burnedpixel.com/blog/beginners-setup-guide-for-ruby-node-git-github-on-your-mac/)

## Clone this repo

Once you have git working, navigate to your projects folder (wherever you keep your projects)

``cd projectfolder``

If you don't have one, make one by typing

``mkdir foldername``

(then change into that directory by typing ``cd foldername``)

Clone the repository (this will make a folder and pull this code onto your computer)

``git clone https://github.com/carbonfive/stylegun.git``

## Rename the directory

Change the name of the repo to something specific to your project

``mv oldname newname``

## Move into the new directory 

``cd newnamefolder``

## Setting up your environment

Make sure you're in the folder by typing (in your terminal)

``pwd``

(print working directory)

Install Middleman

``gem install middleman``

Then, run the server to see your stylegun and changes with

``middleman server``

Open the address in your browser (localhost:4567) and there's your page!

## Adding graphic assets

Open the folder (through your GUI or through the command line)

`` open . ``

Open Source, then Images and add images or graphics there.


## Customizing styles

Open the whole folder in your text editor (Sublime, Atom, Brackets, etc). 

In the Source folder, you will find the stylesheets folder. In stylesheets, you will see partials for Fonts, Colors, Logo, and Hero Image.

You only need to edit the partials, which are the stylesheets starting with a "_", for example "_fonts". You shouldn't have to edit "_stylegunstyles" but you can if you are trying to change the layout of stylegun.

You can add hex codes, images and fonts in the partials.

To view the changes you've made, go back to your command line interface (terminal). In your terminal, run the server by typing:

``middleman server``

Open the address in your browser (localhost:4567) and there's your page!

## Push up to Github

(coming soon)

## Making a Github page

(coming soon)

## Branching or Tagging
(coming soon)

* For multiple styles

# References

* What is middleman? http://benfrain.com/understanding-middleman-the-static-site-generator-for-faster-prototyping/
