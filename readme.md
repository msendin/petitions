# We The People petitions application

Drupal 7 code base used to build an application that lets users create and sign petitions.
## Goals

President Obama is committed to creating the most open and participatory government in our nation’s history, and this petitioning platform is a key part of that initiative. In September, 2011, the White House launched [We the People](http://petitions.whitehouse.gov), a powerful and simple way to petition the Obama Administration to take action on a range of issues. If a petition gathers a minimum number of signatures in a defined amount of time, policy officials review it and publish an official response.
## Requirements

* Drupal 7.x
* MySQL 5.x
* MongoDB 1.8
* PHP 5.2 or 5.3

*Recommended:*

* RAM +512 M
* Dedicated MongoDB server (this dependency will be removed soon, see “Roadmap”)

## Usage

Site visitors can create a user account, log in, and create petitions. Petition creators can share the URL for their petition to generate signatures. When the petition crosses a certain threshold, the petition becomes "public" and is listed as an open petition on the site's "open petitions" page.

Visitor can sign petitions. Petitions that receive a designated number of signatures (at the White House the number is 25,000 in one month) get a response.

For installation instructions, see INSTALL.txt.

NOTE: Setting up the application and configuring it for use in your organization’s context requires Drupal development experience.  The application ships with a similar design (theme) to what is used on petitions.whitehouse.gov and needs to be customized for use by others using standard Drupal 7 themeing conventions. The application also ships with various user interface elements, user account settings, and other configurations that users should expect to customize using standard Drupal 7 techniques and conventions.

## Roadmap

Have an idea or question about future features for We the People? Let us know by opening a ticket on GitHub or emailing us directly: WeThePeopleIdeas@who.eop.gov.


## Contributing

Anyone is encouraged to contribute to the project by [forking](https://help.github.com/articles/fork-a-repo) and submitting a pull request. (If you are new to GitHub, you might start with a [basic tutorial](https://help.github.com/articles/set-up-git).) 
## License

This project constitutes a work of the United States Government and is not subject to domestic copyright protection under 17 USC § 105.