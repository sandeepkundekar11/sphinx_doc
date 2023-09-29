**5.Tailwind Library (Daisy UI)**
======================================

**5.1 Introduction**
-----------------------
Daisy UI is a utility-first CSS framework designed to accelerate web development. It's built on top of Tailwind CSS and provides a set of pre-designed components and utility classes that you can use to style your web applications.

**5.2 Getting Started**
-------------------------

**5.2.1 Installation**
^^^^^^^^^^^^^^^^^^^^^^^^

To start using Daisy UI, you'll need to include it in your project. You can install it via npm:

.. code-block:: bash

    npm install daisyui


**5.2.2 Basic Usage**
^^^^^^^^^^^^^^^^^^^^^^^^^^

Once installed, import Daisy UI's CSS file into your project:

.. code-block:: bash

    @import 'daisyui';

Now, you can start using Daisy UI's components and utility classes in your HTML files.


**5.3 Components**

Daisy UI provides a range of pre-designed components that you can use in your projects. Here are some of the key components:

**5.2.1 Alerts**
^^^^^^^^^^^^^^^^^

Alerts provide feedback messages to users.

.. code-block:: html

    <div class="alert alert-success">
       Success! Your changes have been saved.
    </div>

**5.2.2 Buttons**
^^^^^^^^^^^^^^^^^^

Buttons are interactive elements that trigger actions.

.. code-block:: html

    <button class="btn btn-primary">Click me</button>

**5.2.3 Card**
^^^^^^^^^^^^^^^

Cards are containers for organizing content.

.. code-block:: html

    <div class="card">
      <div class="card-header">Header</div>
      <div class="card-body">Content</div>
    </div>

**5.2.4 Forms**
^^^^^^^^^^^^^^^^^

Forms provide input fields for user interaction.

.. code-block:: html

    <form>
      <input class="form-input" type="text" placeholder="Username">
    </form>

**5.2.5 Modals**
^^^^^^^^^^^^^^^^^

Modals are pop-up windows for displaying additional content.

.. code-block:: html

    <div class="modal">
       <div class="modal-box">
         <div class="modal-header">Modal Title</div>
         <div class="modal-body">Modal Content</div>
      </div>
    </div>

**5.2.6 Navigation**
^^^^^^^^^^^^^^^^^^^^^

Navigation elements help users move around the website.

.. code-block:: html

    <nav class="navbar">
      <ul class="navbar-menu">
         <li><a href="#">Home</a></li>
         <li><a href="#">About</a></li>
         <li><a href="#">Contact</a></li>
         <li><a href="#">Services</a></li>
      </ul>
    </nav>

**5.2.7 Typography**
^^^^^^^^^^^^^^^^^^^^^^

Typography classes help control the appearance of text like font and font weight.

.. code-block:: html

    <p class="text-lg font-semibold">Heading</p>
    <p class="text-2lg font-bold">Heading</p>


**5.3 Utilities**
-----------------------

Daisy UI offers a comprehensive set of utility classes for styling elements. Here are some commonly used utilities:

**5.3.1 Color**
^^^^^^^^^^^^^^^^

.. code-block:: html
    
    <div class="bg-blue-500 text-white">Blue Background</div>

**5.3.2 Spacing**
^^^^^^^^^^^^^^^^^^

.. code-block:: html

    <div class="p-4">Padding</div>


**5.3.3 Sizing**
^^^^^^^^^^^^^^^^^^

.. code-block:: html

    <div class="w-24 h-24">Width and Height</div>

**5.3.4 Visibility**
^^^^^^^^^^^^^^^^^^^^^^

.. code-block:: html

    <div class="hidden">Hidden Element</div>

**5.4 Themes**
---------------

daisyUI comes with a number of themes, which you can use with no extra effort. Each theme defines a set of colors which will be used on all daisyUI elements. To use a theme, add its name in tailwind.config.js and activate it by adding data-theme attribute to HTML tag:

.. code-block:: bash

    module.exports = {
        //...
        daisyui: {
            themes: ["light", "dark", "cupcake"],
        },
    }

.. code-block:: html

    <html data-theme="cupcake"></html>


**5.5 Integration with Frameworks**
-------------------------------------

Daisy UI can be integrated with several popular frameworks like as follow:

- **Tailwind css**
- **laravel**
- **Vue.js**
- **React.js**




