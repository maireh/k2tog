# k2tog

k2tog is a shared project between Erin Heyming and Maire Howard.

Erin and Maire are bringing up our knit2together.us site using Hugo. Our target user is a beginning knitter. Over time we will taylor it more and more as a knitting site that integrates well with Ravelry.

We are starting with the Academic theme even though this is not likely to be our final theme.

I have copyrighted the images specific to knit2together. Contact us if you want to use them.

## How to install.

1. Install k2tog:

        git clone https://github.com/maireh/k2tog.git

2. [Install Hugo](https://georgecushen.com/create-your-website-with-hugo/#installing-hugo)

        cd k2tog       

2. Install tranquilpeak theme (from the tranquilpeak documentation)

        ### For people who want to use the original version of Tranquilpeak without modifications (users)		

		Go to the directory where you have your Hugo site and run:		

		```shell
		mkdir themes
		cd themes
		git clone https://github.com/kakawait/hugo-tranquilpeak-theme.git
		```	

		More information on [user documentation](https://github.com/kakawait/hugo-tranquilpeak-theme/blob/master/docs/user.md) to install and configure the theme  		

		### For people who want to create their own version of tranquilpeak (developers) 		
		2. Follow [developer documentation](https://github.com/kakawait/hugo-tranquilpeak-theme/blob/master/docs/developer.md) to edit and build the theme 


3. Run the hugo site for development

        hugo server -D -w -v -d public


4. Set up your local site for Git integration

 TODO: test if this just works or if there are extra steps. .gitignore might be too mac specific


## Development Process

These instructions are for Erin Heyming and Maire Howard as it is for development of the [Knit 2 Together](www.knit2together.us) web site. 

 TODO: define the development and deployment process.


