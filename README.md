ey-cloud-recipes for Piggybaggy
===============================
This is a modified tree of Engine Yard deployment recipes,
as used in Piggybaggy application instances.

Modifications:
* PostGIS 2 extension enabled on the PostgreSQL database.

Installation
============

Follow these steps to use custom deployment recipes with your applications.

* Install the engineyard gem:
  $ gem install engineyard
* Add any custom recipes or tweaks to your copy of these recipes.
* Upload them with: `ey recipes upload -e ENV`, where ENV is the name of your environment in Engine Yard Cloud. This may be different than your Rails environment name.
* Once you have completed these steps, each rebuild will run the your
  recipes after the default Engine Yard recipes have run. When you
  update your recipes, just re-run `ey recipes upload -e ENV`.

Continuous Integration
======================

[![Build Status](https://secure.travis-ci.org/engineyard/ey-cloud-recipes.png?branch=master)](http://travis-ci.org/engineyard/ey-cloud-recipes)
