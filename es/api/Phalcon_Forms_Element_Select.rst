Class **Phalcon\\Forms\\Element\\Select**
=========================================

*extends* abstract class :doc:`Phalcon\\Forms\\Element <Phalcon_Forms_Element>`

*implements* :doc:`Phalcon\\Forms\\ElementInterface <Phalcon_Forms_ElementInterface>`

Component SELECT (choice) for forms


Methods
-------

public  **__construct** (*string* $name, [*object|array* $options], [*array* $attributes])

Phalcon\\Forms\\Element constructor



public :doc:`Phalcon\\Forms\\Element <Phalcon_Forms_Element>`  **setOptions** (*array|object* $options)

Set the choice's options



public *array|object*  **getOptions** ()

Returns the choices' options



public *this*  **addOption** (*array* $option)

Adds an option to the current options



public *string*  **render** ([*array* $attributes])

Renders the element widget returning html



public  **setForm** (*unknown* $form) inherited from Phalcon\\Forms\\Element

Sets the parent form to the element



public  **getForm** () inherited from Phalcon\\Forms\\Element

Returns the parent form to the element



public  **setName** (*unknown* $name) inherited from Phalcon\\Forms\\Element

Sets the element name



public  **getName** () inherited from Phalcon\\Forms\\Element

Returns the element name



public :doc:`Phalcon\\Forms\\ElementInterface <Phalcon_Forms_ElementInterface>`  **setFilters** (*array|string* $filters) inherited from Phalcon\\Forms\\Element

Sets the element filters



public  **addFilter** (*unknown* $filter) inherited from Phalcon\\Forms\\Element

Adds a filter to current list of filters



public *mixed*  **getFilters** () inherited from Phalcon\\Forms\\Element

Returns the element filters



public :doc:`Phalcon\\Forms\\ElementInterface <Phalcon_Forms_ElementInterface>`  **addValidators** (*unknown* $validators, [*unknown* $merge]) inherited from Phalcon\\Forms\\Element

Adds a group of validators



public  **addValidator** (*unknown* $validator) inherited from Phalcon\\Forms\\Element

Adds a validator to the element



public  **getValidators** () inherited from Phalcon\\Forms\\Element

Returns the validators registered for the element



public *array*  **prepareAttributes** ([*array* $attributes], [*boolean* $useChecked]) inherited from Phalcon\\Forms\\Element

Returns an array of prepared attributes for Phalcon\\Tag helpers according to the element parameters



public :doc:`Phalcon\\Forms\\ElementInterface <Phalcon_Forms_ElementInterface>`  **setAttribute** (*string* $attribute, *mixed* $value) inherited from Phalcon\\Forms\\Element

Sets a default attribute for the element



public *mixed*  **getAttribute** (*string* $attribute, [*mixed* $defaultValue]) inherited from Phalcon\\Forms\\Element

Returns the value of an attribute if present



public  **setAttributes** (*unknown* $attributes) inherited from Phalcon\\Forms\\Element

Sets default attributes for the element



public  **getAttributes** () inherited from Phalcon\\Forms\\Element

Returns the default attributes for the element



public :doc:`Phalcon\\Forms\\ElementInterface <Phalcon_Forms_ElementInterface>`  **setUserOption** (*string* $option, *mixed* $value) inherited from Phalcon\\Forms\\Element

Sets an option for the element



public *mixed*  **getUserOption** (*string* $option, [*mixed* $defaultValue]) inherited from Phalcon\\Forms\\Element

Returns the value of an option if present



public :doc:`Phalcon\\Forms\\ElementInterface <Phalcon_Forms_ElementInterface>`  **setUserOptions** (*array* $options) inherited from Phalcon\\Forms\\Element

Sets options for the element



public *array*  **getUserOptions** () inherited from Phalcon\\Forms\\Element

Returns the options for the element



public  **setLabel** (*unknown* $label) inherited from Phalcon\\Forms\\Element

Sets the element label



public  **getLabel** () inherited from Phalcon\\Forms\\Element

Returns the element label



public *string*  **label** ([*array* $attributes]) inherited from Phalcon\\Forms\\Element

Generate the HTML to label the element



public :doc:`Phalcon\\Forms\\ElementInterface <Phalcon_Forms_ElementInterface>`  **setDefault** (*mixed* $value) inherited from Phalcon\\Forms\\Element

Sets a default value in case the form does not use an entity or there is no value available for the element in _POST



public *mixed*  **getDefault** () inherited from Phalcon\\Forms\\Element

Returns the default value assigned to the element



public *mixed*  **getValue** () inherited from Phalcon\\Forms\\Element

Returns the element value



public  **getMessages** () inherited from Phalcon\\Forms\\Element

Returns the messages that belongs to the element The element needs to be attached to a form



public  **hasMessages** () inherited from Phalcon\\Forms\\Element

Checks whether there are messages attached to the element



public  **setMessages** (*unknown* $group) inherited from Phalcon\\Forms\\Element

Sets the validation messages related to the element



public  **appendMessage** (*unknown* $message) inherited from Phalcon\\Forms\\Element

Appends a message to the internal message list



public  **clear** () inherited from Phalcon\\Forms\\Element

Clears every element in the form to its default value



public  **__toString** () inherited from Phalcon\\Forms\\Element

Magic method __toString renders the widget without atttributes



