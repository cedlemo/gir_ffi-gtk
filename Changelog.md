## Change Log
All notable changes to this project will be documented in this file. See the
Git log for all changes.

### 0.7.2 / 2014-09-22

* Require at least Ruby 1.9.3
* Add overrides for Gtk::TreePath
* Add overrides for Gtk::MessageDialog.new
* Make other Ruby threads run during Gtk.main loop
* Update dependencies
* Update examples

### 0.7.1 / 2014-03-25

* Fix Gtk::Builder#connect_signals_full by updating dependency on GirFFI
* Only override Gtk::Menu#popup if needed
* Test both Gtk+ 2 and 3
* Provide constructors for Gtk::RadioButton if needed

### 0.7.0 / 2014-01-11

* Update dependency on GirFFI

### 0.6.0 / 2013-06-09

* Update dependency on GirFFI

### 0.5.0 / 2013-01-19

* Update dependency on GirFFI

### 0.4.1 / 2012-09-22

* New TreeView example (thanks, Kasper Johansen)
* Implement Gtk::Menu#popup
* Update dependency on GirFFI so interfaces can wrap pointers

### 0.4.0 / 2012-08-24

* Initial release
