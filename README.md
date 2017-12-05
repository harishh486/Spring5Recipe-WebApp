# Spring Boot Recipe Application

Concepts Used:

1) Spring JPA Entity Relationships
@one-one
@one-many
@many-one
@many-many

2) Spring Data Repository
3) Spring Data Base Initialization
   a)load.sql
   b)schema.sql


3) Spring Data JPA Query methods

4) SpringMVC


Application flow:
================

  1) Creating the bootstrap class and return back the repository.
     we save a list of recipes to the recipeRepository.
 
  2) We inject this in to the service and manipulate and return back to index controller and assign it to the property of view       model of recipes, then we display list of recipes through the Thymeleaf template.
  
  
  Integrated with CIRCLE CI
  ==========================
  testing the Circle CI
