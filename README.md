# k2tog

k2tog is a shared project between Erin Heyming and Maire Howard.

Erin and Maire are bringing up our knit2together.us site using Hugo. Our target user is a beginning knitter. Over time we will taylor it more and more as a knitting site that integrates well with Ravelry.

We have copyrighted the images specific to knit2together. Contact us if you want to use them.

## How to install.

1. Install k2tog:

        git clone https://github.com/maireh/k2tog.git

2. [Install Hugo](https://georgecushen.com/create-your-website-with-hugo/#installing-hugo)

        cd k2tog       

2. Install tranquilpeak theme (from the tranquilpeak documentation)
    		

	Go to the directory where you have your Hugo site and run:		

		```shell
		mkdir themes
		cd themes
		git clone https://github.com/kakawait/hugo-tranquilpeak-theme.git
		```	

	For people who want to use the original version of Tranquilpeak without modifications (users), use information on [user documentation](https://github.com/kakawait/hugo-tranquilpeak-theme/blob/master/docs/user.md) to install and configure the theme  		

	For people who want to create their own version of tranquilpeak (developers) 		
	Follow [developer documentation](https://github.com/kakawait/hugo-tranquilpeak-theme/blob/master/docs/developer.md) to edit and build the theme 


3. Run the hugo site for development

        hugo server -D -w -v -d public


4. Set up your local site for Git integration

 	TODO: Maire and Erin will define the Github integration process. So far Maire's kludgy process just works but Erin has a better process. The only thing I would recomend is to get a git markdown renderer so you can see README.me before you push. I am using [grip](https://github.com/joeyespo/grip).


## Development Process

These instructions are for Erin Heyming and Maire Howard as it is for development of the [Knit 2 Together](www.knit2together.us) web site. 

We don't have the final process for deployment yet, but for now we are just deploying the non-draft generated files. In the future we might use rsync or nanobox.

Make sure you delete the public folder since the hugo server generates localhost links. Then run hugo in the k2tog directory.

		hugo

Then copy the static files in public folder to the host and put in the knit2together.us directory. Maire is using yaml.



