#Material APEX - Beta
This is a full featured Material Design Theme for APEX 5.

Here's a demo: https://apex.oracle.com/pls/apex/f?p=12192

The APEX application export is included in this repo.

##Changelog
####0.8.1
- Content is now offset when sidebar is fixed
- Fixed navigation bar icons alignment on mobile
- Select list is now aligned properly with text fields
- Autocomplete item now has a material design look and feel
- Cascading LOVs are now supported
- Popup LOV in Tabular Forms are now supported
- Login Screen has a new template called "Page - Clean"
- Region titles are now aligned according to the specified template option 

####0.8.0
- **Theme Roller Support**, primary and secondary colors are now choosable from the theme roller!
- **New easier grid layout system**  [(view)](https://apex.oracle.com/pls/apex/f?p=12192:11)
- **New Date Picker**. We let go of the "pickadate.js" plugin for better compabilitiby. [(view)](https://apex.oracle.com/pls/apex/f?p=12192:25)
- The hamburger menu is now selectable as a component on page 0. Can be controled for conditions or authorization schemes.
- Now uses Official Google Icon web font
- Added template option for button regarding icon float 
- Modal now prevents scrolling
- Removed the #APPLICATION_NAME# substitution string. Now uses the default #LOGO# substitution string
- Reworked on the Grid Documentation
- More documentation enhancements
- Fixed an issue with Materialbox not re-opening
- Fixed the success message layout
- Fixed Fixed Action Button display
- Fixed Modal Fixed Footer
- Fixed Sidenav height
- More...

##Automatic Install
- Import the APEX application ```12192.sql``` in your workspace.

##Manual Install
- Fork the project on Github
- `npm install`
- `bower install materialize`
- `npm start`

You can now use your own Sass (I suggest you take a look at this: https://github.com/vincentmorneau/apex-gulpfile-sass)

---

Inspired by http://materializecss.com/  

You can help by filling issues through Github.