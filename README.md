Bootstrap 3 - Sublime Plugin
==================
A Fork from https://github.com/JasonMortonNZ/re-sublime-plugin. The syntax is a little bit awkward. So, i am renaming it to 're-'.

A sublime plugin complete with Bootstrap 3 snippets

Feel free to let me know what else you want added via:

- Twitter [@JasonMortonNZ](https://twitter.com/jasonmortonnz)
- [Issues](https://github.com/JasonMortonNZ/re-sublime-plugin/issues)


## What's included - contents
- [Installation](#installation)
- [CDN](#cdn)
- [Templates](#templates)
- [Forms](#forms)
- [Tables](#tables)
- [Input](#input-fields-form-fields)
- [Alerts](#alerts)
- [Badges](#badges)
- [Breadcrumbs](#breadcrumbs)
- [Buttons](#buttons)
- [Carousel](#carousel)
- [Grid](#grid)
- [Images](#images)
- [Icons](#icons)
- [Labels](#labels)
- [Pagination](#pagination)
- [Navigation](#navigation)
- [Panels](#panels)
- [List Groups](#list-groups)
- [Media Objects](#media-objects)
- [Icons](#icons)
- [Clearfix](#clearfix)
- [Wells](#wells)
- [License](#license)


### Installation

There are 3 methods for installing this plugin.

1. Search for "Bootstrap 3 Snippets" via the "Package Control: Install Packages" menu.
**Note:** If you don't have Sublime Package Control installed, you can find out how to install it here [https://sublime.wbond.net/installation](https://sublime.wbond.net/installation)

2. Clone the repository into your Sublime Text 2/3 packages directory.
`git clone https://github.com/JasonMortonNZ/re-sublime-plugin.git

3. Download the .zip file and unzip it into your Sublime Text 2/3 packages directory.
**Note:** You can find your Sublime Text 2/3 packages directory by going to Preferences > Browse Packages.

### CDN

| Component                      | Snippet code                   |
|------------------------------- | :-----------------------------:|
| CDN link (both CSS & JS)       | re-cdn                        |
| CDN link (CSS only)            | re-cdn:css                    |
| CDN link (JS only)             | re-cdn:js                     |

### Templates

| Component                      | Snippet code                   |
|------------------------------- | :-----------------------------:|
| HTML5 Template Layout          | re-template:html5             |

### Forms

| Component       				 | Snippet code        			  |
|------------------------------- | :-----------------------------:|
| Form            				 | re-form            			  |
| Inline Form     				 | re-form:inline     			  |
| Horizontal Form 				 | re-form:horizontal 			  |

### Tables

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------: |
| Table                    		 | re-table                      |
| Bordered Table           		 | re-table:bordered             |
| Condensed Table          		 | re-table:condensed            |
| Hover Table              		 | re-table:hover                |
| Striped Table            		 | re-table:striped              |

### Input Fields (Form fields)

**Note:** you can add " :h " to the end of any input field snippet to make it compatible with Bootstrap 3 horizontal forms. **E.g.**
- re-input:text:h
- re-input:hidden:h


| Component                		 | Snippet code                   | Options |
|------------------------------- | :----------------------------: | :-----:	|
| Label		 					 | re-input:label   			  |    		|
| Text Input               		 | re-input:text 				  | :h 		|
| Email Input 					 | re-input:email   			  | :h 		|
| Password Input				 | re-input:password  			  | :h 		|
| Hidden Input					 | re-input:hidden  			  | :h 		|
| Url Input						 | re-input:url 	 			  | :h 		|
| Color Input 					 | re-input:color   			  | :h 		|
| Number Input 					 | re-input:number   			  | :h 		|
| Range Input 					 | re-input:range   			  | :h 		|
| Date Input 					 | re-input:date   			  | :h 		|
| Week Input 					 | re-input:week   			  | :h 		|
| Month Input 					 | re-input:month   			  | :h 		|
| Time Input 					 | re-input:time   			  | :h 		|
| Tel Input 					 | re-input:tel   	 			  | :h 		|
| Search Input 					 | re-input:search   			  | :h 		|
| Reset Input 					 | re-input:reset   			  | :h 		|
| Submit Input 					 | re-input:submit   			  | :h 		|
| Checkbox Input 				 | re-input:checkbox  			  | :h 		|
| Radio Box Input 				 | re-input:radio  			  | :h 		|
| Select Box 	 				 | re-select		  			  | :h 		|

### Alerts

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------: |
| Alert Box (Default)			 | re-alert 					  |
| Danger Alert Box				 | re-alert:danger 			  |
| Info Alert Box				 | re-alert:info				  |
| Success Alert Box              | re-alert:success              |
| Warning Alert Box				 | re-alert:warning			  |

### Badges

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------: |
| Badge (Default) 				 | re-badge 					  |

### Breadcrumbs

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| Breadcrumbs                    | re-breadcrumbs                |

### Carousel

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------: |
| Carousel	      				 | re-carousel	       			  |

### Buttons

**Note:** all button snippets below can have any of the following options append to the end of the snippet *.
- :danger
- :default
- :disabled
- :info
- :primary
- :success
- :warning

**An example:**
- re-button:success
- re-large-button:disabled
- re-block-button:warning

| Component                		 | Snippet code                   | Options |
|------------------------------- | :----------------------------: | :-----:	|
| Button		 				 | re-button					  |  *		|
| Block Button	 				 | re-block-button				  |  *		|
| Mini Button		 			 | re-xs-button				  |	 *		|
| Small Button		 			 | re-sm-button				  |	 *		|
| Large Button		 			 | re-lg-button				  |	 *		|

### Grid

**Note:** The re-col snippet can be used both on its own or with the addition of a colon followed by the number of columns required: **E.g.**

- re-col
- re-col:6
- re-col:12

| Component                		 | Snippet code                   | Options |
|------------------------------- | :----------------------------: | :-----:	|
| Column		 				 | re-col						  | :1-12	|
| Row			 				 | re-row						  |  		|
| Container		 				 | re-container				  |			|

### Icons

| Component                      | Snippet code                   |
|------------------------------- | :-----------------------------:|
| Glyphicon		                 | re-icon:glyphicon             |
| Icon (Font Awesome)		     | re-icon                       |

### Images

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------: |
| Thumbnail	 					 | re-thumbnail 				  |
| Thumbnail with content		 | re-thumbnail:content		  |

### Labels

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------: |
| Label		 					 | re-label 	 				  |
| Danger Label					 | re-label:danger				  |
| Info Label					 | re-label:info 				  |
| Success Label					 | re-label:success			  |
| Warning Label					 | re-label:warning			  |

### Pagination

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------: |
| Pager		 					 | re-pager	 				  |
| Aligned Pager             	 | re-pager:aligned 			  |
| Pagination					 | re-pagination				  |
| Pagination:small				 | re-pagination:small			  |
| Pagination:large				 | re-pagination:large			  |

### Navigation

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------: |
| Navbar (basic navbar)			 | re-navbar	 				  |
| Navbar Brand Element			 | re-navbar:brand				  |
| Navbar Button					 | re-navbar:button			  |
| Navbar Form 					 | re-navbar:form 				  |
| Navbar Link 					 | re-navbar:link 				  |
| Navbar Text 					 | re-navbar:text 				  |
| Navbar Fixed-Botton			 | re-navbar:fixed-bottom		  |
| Navbar Fixed-Top				 | re-navbar:fixed-top			  |
| Navbar Inverse				 | re-navbar:inverse			  |
| Navbar Responsive				 | re-navbar:responsive		  |
| Navbar Static-Top				 | re-navbar:static-top		  |

### Jumbotron

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------: |
| Jumbotron (ex Hero Unit)		 | re-jumbotron 				  |

### Panels

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| Panel                          | re-panel                      |
| Panel (contextual)             | re-panel:{warning,success,info,danger,primary}                  |
| Panel (with heading)           | re-panel:heading              |
| Panel (with footer)            | re-panel:footer               |

### List-groups

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| List group                     | re-list-group                 |
| List group (with badges)       | re-list-group:badges          |
| List group (linked list)       | re-list-group:linked          |
| List group (with content)      | re-list-group:content         |

### Media Objects

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| Media Object                   | re-media-object               |

### Clearfix

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| Clearfix                       | re-clearfix                   |

### Wells

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| Well                           | re-well                       |
| Well (small)                   | re-well:sm                    |
| Well (large)                   | re-well:lg                    |

### License

Bootstrap 3 - Sublime Plugin is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
