Introduction/Instruction text
===============================

This file is the first page where the visitors of you video portal will see. It
asks for the visitor's username (Not the password!!!). It also provides the
instructions how to use the tool.

.. image:: introduction.png
  :width: 800
  :alt: The Introduction Page

To edit, Find the file "index.php". In the file find the comment "Start Custom".

.. code-block:: html
    :emphasize-lines: 1

    <!-- Start Custom -->
    <p>Use your Cal Poly user name (no password needed). I will never ask for your password!</p>
    <p>Please start and end the video with the Start and Done buttons. Do not close the window or tab before you have hit Done.</p>
    <!-- End Custom -->

In between "Start Custom" and "End Custom" is where you can edit the
introduction/instruction text. You must write your text in HTML.
