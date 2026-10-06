..
    Zephyr Project documentation main file

.. _zephyr-home:

وثائق مشروع Zephyr
############################

.. raw:: html

   <script>
     function openVersionSelector() {
       // Open the mobile menu if visible
       var mobileMenu = document.querySelector('[data-toggle="wy-nav-top"]');
       if (mobileMenu && mobileMenu.offsetParent !== null) {
         mobileMenu.click();
       }
       // Open the version selector
       var versionSelector = document.querySelector('[data-toggle="rst-current-version"]');
       if (versionSelector) {
         versionSelector.click();
       }
     }
   </script>

.. only:: release

   .. admonition:: مرحبًا بك في وثائق مشروع Zephyr للإصدار |version|.
      :class: welcome

      .. raw:: html

         <p>
           استخدم <a href="#" onclick="openVersionSelector(); return false;">محدد الإصدارات</a>
           للاطلاع على وثائق إصدارات Zephyr الأخرى.
         </p>

.. only:: development

   .. admonition:: مرحبًا بك في وثائق مشروع Zephyr لفرع ``main`` (|version|).
      :class: welcome

      .. raw:: html

         <p>
           استخدم <a href="#" onclick="openVersionSelector(); return false;">محدد الإصدارات</a>
           للاطلاع على وثائق الإصدارات السابقة.
         </p>

.. raw:: html
   :file: index.html

.. toctree::
   :maxdepth: 1
   :hidden:

   introduction/index.rst
   develop/index.rst
   kernel/index.rst
   services/index.rst
   build/index.rst
   connectivity/index.rst
   hardware/index.rst
   contribute/index.rst
   project/index.rst
   security/index.rst
   safety/index.rst
   samples/index.rst
   boards/index.rst
   releases/index.rst
