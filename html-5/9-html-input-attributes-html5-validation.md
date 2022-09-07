## HTML Input Attributes

**Content**

1.HTML Input Attributes

1.1 The value Attribute

1.2 The readonly Attribute

1.3 The disabled Attribute

1.4 The size Attribute

1.5 The maxlength Attribute

1.6 The min and max Attributes

1.7 The placeholder Attribute

1.8 The required Attribute

1.9 The autofocus Attribute

1.10 The height and width Attributes

2\. References

## 1.HTML Input Attributes

-   The different attributes for the HTML \<input\> element are **value,** **readonly, disabled, size, maxlength, min and max, placeholder,** required, autofocus, height and width.

## 1.1 The value Attribute

-   The input value attribute specifies an initial value for an input field:

**Exmple:** Input fields with initial (default) values:

![](media/7c611f00006c61c52cd3d8615ad460c6.png)

## 1.2 The readonly Attribute

-   The input readonly attribute specifies that an input field is read-only.
-   A read-only input field cannot be modified (however, a user can tab to it, highlight it, and copy the text from it).
-   The value of a read-only input field will be sent when submitting the form!

**Exmple:** A read-only input field:

![](media/e6cce1e5bc67cc584b9b2920a13b934d.png)

## 1.3 The disabled Attribute

-   The input disabled attribute specifies that an input field should be disabled.
-   A disabled input field is unusable and un-clickable.
-   The value of a disabled input field will not be sent when submitting the form!

**Exmple:** A disabled input field:

![](media/12af531df07134449049876bffb4e0bf.png)

## 1.4 The size Attribute

-   The input size attribute specifies the visible width, in characters, of an input field.
-   The default value for size is 20.

**Note:** The size attribute works with the following input types: text, search, email, and password.

**Exmple:** Set a width for an input field:

![](media/eecd3ba221cba9ecf886c3e32c04bf61.png)

## 1.5 The maxlength Attribute

-   The input maxlength attribute specifies the maximum number of characters allowed in an input field.

**Note:** When a maxlength is set, the input field will not accept more than the specified number of characters. However, this attribute does not provide any feedback. So, if you want to alert the user, you must write JavaScript code.

**Exmple:** Set a maximum length for an input field:

![](media/96b33ad00ba8de78beb3652021aa4d92.png)

## 1.6 The min and max Attributes

-   The input min and max attributes specify the minimum and maximum values for an input field.
-   The min and max attributes work with the following input types: number, date.

**Note:** Use the max and min attributes together to create a range of legal values.

**Exmple:** Set a max date, a min date, and a range of legal values:

![](media/4dbf9793b59bf2ca56c54e85683cc4ac.png)

## 1.7 The placeholder Attribute

-   The input placeholder attribute specifies a short hint that describes the expected value of an input field (a sample value or a short description of the expected format).
-   The short hint is displayed in the input field before the user enters a value.
-   The placeholder attribute works with the following input types: text, search, email, and password.

**Exmple:** An input field with a placeholder text:

![](media/3dd322a2d4e920e82ad37ed0d01f31be.png)

## 1.8 The required Attribute

-   The input required attribute specifies that an input field must be filled out before submitting the form.
-   The required attribute works with the following input types: text, search, email, password, number, checkbox, radio, and file.

**Exmple:** A required input field:

![](media/ef19dab472e32ad6127338c73f6d1915.png)

## 1.9 The autofocus Attribute

-   The input autofocus attribute specifies that an input field should automatically get focus when the page loads.

**Exmple:** Let the "First name" input field automatically get focus when the page loads:

![](media/5f3a5735b186e3d0f9c5177f1b0f81d4.png)

## 1.10 The height and width Attributes

-   The input height and width attributes specify the height and width of an \<input type="image"\> element.

**Note:** Always specify both the height and width attributes for images. If height and width are set, the space required for the image is reserved when the page is loaded. Without these attributes, the browser does not know the size of the image, and cannot reserve the appropriate space to it. The effect will be that the page layout will change during loading (while the images load).

**Exmple:** Define an image as the submit button, with height and width attributes:

![](media/e58083b95facd6b0fe95176ae8fc3fa0.png)

## 2. References

1\. https://www.w3schools.com/html/html_form_attributes.asp
