# PhpStorm Code style settings

## Description

* PHP: based on Symfony2
    * empty line before the return statement
    * no comma after last array item

* JavaScript/Typescript: based on JavaScript Standard Style
    * indent 4 spaces
    * semi-colons
    * chained indented calls

* vue.js Components (.vue) 
    * same as Typescript

* SCSS/LESS: based on PhpStorm Default
    * indent 4 spaces

* HTML: based on PhpStorm Default
    * Wrap attributes = Chop down if long

## Import

### IDE

1. _File_ > _Settings_
2. _Editor_ > _Code Style_
3. Select the _three dots_ next to _Scheme_
4. Select _Import Scheme …_
5. Select _IntelliJ Idea Code Style XML_
6. Select the XML file and import

1. _File_ > _Settings_
2. _Editor_ > _Inspections_
3. Select the _three dots_ next to _Profile_
4. Select _Import Profile …_
5. Select _Profile Default.xml_
5. Select the XML file and import

### Project

1. Open your project
2. Follow steps 1-3 as above
3. Select _Copy to Project …_ and confirm the following dialog (Overwrite)
4. Apply the new styles to your project


# PhpStorm Inspections settings

* PHP: ignore PHPDoc comments if type hints are sufficient

## Import

### IDE

1. _File_ > _Settings_
2. _Editor_ > _Inspections_
3. Select the _three dots_ next to _Profile_
4. Select _Import Profile …_
5. Select _Profile Default.xml_
6. Select the XML file and import
