.. raw:: html

   <a href="https://www.zephyrproject.org">
     <p align="center">
       <picture>
         <source media="(prefers-color-scheme: dark)" srcset="doc/_static/images/logo-readme-dark.svg">
         <source media="(prefers-color-scheme: light)" srcset="doc/_static/images/logo-readme-light.svg">
         <img src="doc/_static/images/logo-readme-light.svg">
       </picture>
     </p>
   </a>

   <a href="https://bestpractices.coreinfrastructure.org/projects/74"><img src="https://bestpractices.coreinfrastructure.org/projects/74/badge"></a>
   <a href="https://scorecard.dev/viewer/?uri=github.com/zephyrproject-rtos/zephyr"><img src="https://api.securityscorecards.dev/projects/github.com/zephyrproject-rtos/zephyr/badge"></a>
   <a href="https://github.com/zephyrproject-rtos/zephyr/actions/workflows/twister.yaml?query=branch%3Amain"><img src="https://github.com/zephyrproject-rtos/zephyr/actions/workflows/twister.yaml/badge.svg?event=push"></a>


مشروع Zephyr هو نظام تشغيل آني (RTOS) قابل للتوسع، يدعم معماريات عتادية
متعددة، ومحسّن للأجهزة محدودة الموارد، ومصمم مع مراعاة الأمان.

يعتمد نظام Zephyr على نواة صغيرة الحجم للأنظمة محدودة الموارد، بدءًا من
المستشعرات البيئية المضمنة والأجهزة القابلة للارتداء المزودة بمصابيح LED،
وصولًا إلى الساعات الذكية المتقدمة وبوابات إنترنت الأشياء اللاسلكية.

تدعم نواة Zephyr معماريات متعددة، منها ARM ‏(Cortex-A وCortex-R وCortex-M)
وIntel x86 وARC وTensilica Xtensa وRISC-V وSPARC وMIPS، إضافة إلى عدد كبير من
`اللوحات المدعومة`_.

.. below included in doc/introduction/introduction.rst


البدء
***************

مرحبًا بك في Zephyr! اقرأ `مقدمة Zephyr`_ للتعرّف على نظرة عامة عن المشروع،
واتبع `دليل البدء`_ لتهيئة بيئة التطوير والبدء بإنشاء التطبيقات.

.. start_include_here

دعم المجتمع
*****************

يتوفر دعم المجتمع عبر القوائم البريدية وDiscord. راجع الموارد أدناه لمعرفة
التفاصيل.

.. _project-resources:

الموارد
*********

فيما يلي مجموعة مختصرة من الموارد التي تساعدك على استكشاف المشروع:

البدء
---------------

  | 📖 `وثائق Zephyr`_
  | 🚀 `دليل البدء`_
  | 🙋🏽 `نصائح لطلب المساعدة`_
  | 💻 `أمثلة الشيفرة`_

الشيفرة والتطوير
--------------------

  | 🌐 `مستودع الشيفرة المصدرية`_
  | 📦 `الإصدارات`_
  | 🤝 `دليل المساهمة`_

المجتمع والدعم
---------------------

  | 💬 `خادم Discord`_ للنقاشات المباشرة مع المجتمع
  | 📧 `القائمة البريدية للمستخدمين (users@lists.zephyrproject.org)`_
  | 📧 `القائمة البريدية للمطورين (devel@lists.zephyrproject.org)`_
  | 📬 `القوائم البريدية الأخرى للمشروع`_
  | 📚 `ويكي المشروع`_

تتبّع المشكلات والأمان
---------------------------

  | 🐛 `مشكلات GitHub`_
  | 🔒 `وثائق الأمان`_
  | 🛡️ `مستودع التنبيهات الأمنية`_
  | ⚠️ أبلغ عن الثغرات الأمنية عبر vulnerabilities@zephyrproject.org

موارد إضافية
--------------------
  | 🌐 `موقع مشروع Zephyr`_
  | 📺 `محاضرات Zephyr التقنية`_

.. _موقع مشروع Zephyr: https://www.zephyrproject.org
.. _خادم Discord: https://chat.zephyrproject.org
.. _اللوحات المدعومة: https://docs.zephyrproject.org/latest/boards/index.html
.. _وثائق Zephyr: https://docs.zephyrproject.org
.. _مقدمة Zephyr: https://docs.zephyrproject.org/latest/introduction/index.html
.. _دليل البدء: https://docs.zephyrproject.org/latest/develop/getting_started/index.html
.. _دليل المساهمة: https://docs.zephyrproject.org/latest/contribute/index.html
.. _مستودع الشيفرة المصدرية: https://github.com/zephyrproject-rtos/zephyr
.. _مشكلات GitHub: https://github.com/zephyrproject-rtos/zephyr/issues
.. _الإصدارات: https://github.com/zephyrproject-rtos/zephyr/releases
.. _ويكي المشروع: https://github.com/zephyrproject-rtos/zephyr/wiki
.. _القائمة البريدية للمستخدمين (users@lists.zephyrproject.org): https://lists.zephyrproject.org/g/users
.. _القائمة البريدية للمطورين (devel@lists.zephyrproject.org): https://lists.zephyrproject.org/g/devel
.. _القوائم البريدية الأخرى للمشروع: https://lists.zephyrproject.org/g/main/subgroups
.. _أمثلة الشيفرة: https://docs.zephyrproject.org/latest/samples/index.html
.. _وثائق الأمان: https://docs.zephyrproject.org/latest/security/index.html
.. _مستودع التنبيهات الأمنية: https://github.com/zephyrproject-rtos/zephyr/security
.. _نصائح لطلب المساعدة: https://docs.zephyrproject.org/latest/develop/getting_started/index.html#asking-for-help
.. _محاضرات Zephyr التقنية: https://www.zephyrproject.org/tech-talks
