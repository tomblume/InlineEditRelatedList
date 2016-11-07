## Overview

This app provides all the necessary lightning components to enable inline editing for related list.

## What is in the box

The app provides lightning components for the client side and a controller to handle metatdata and data manipulation in the backend.
The controller can handle any type of object (standard and custom as well). To achieve this, I massivelly used the Salesfroce Rest API mainly "sobject" API(s). 

## Lightning Components

### RelatedListDataGridsComponent

Display all the related lists. The list of related list is extracted from the object layout.

### RelatedListDataGridComponent

Display a specific related list based on the label. Using the label is more user friendly. 
The related list label can set from the app lightning builder.

Both components are availables in the lightning app builder. So just drag&drop and enjoy.

##Testing

The package contains Unit Tests for Apex classes and Static Resources for Rest MockUp.

