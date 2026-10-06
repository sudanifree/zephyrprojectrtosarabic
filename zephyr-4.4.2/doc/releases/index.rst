.. _zephyr_release_notes:

الإصدارات
#########

يُوزع Zephyr على شكل شيفرة مصدرية ونصوص بناء، وليس صورة ثنائية. استخدم
:ref:`west` للحصول على :ref:`الشيفرة <get_the_code>` لإصدار معين، وراجع
`مستودع GitHub`_ للاطلاع على سجل الإصدارات الموسومة كاملًا.

تتوفر الوثائق التقنية للإصدارات الحالية والسابقة على
https://docs.zephyrproject.org/ (استخدم محدد الإصدارات لاختيار الإصدار المطلوب).

.. _supported_releases:

الإصدارات المدعومة
******************

يسرد الجدول أدناه جميع الإصدارات التي ما زالت تحظى بالدعم. ونوصي معظم
المستخدمين بالبدء بـ **أحدث إصدار مستقر** أو **إصدار LTS الحالي**.

.. toctree::
   :hidden:
   :maxdepth: 1
   :glob:
   :reversed:

   release-notes-3.7
   release-notes-4.[3-5]
   migration-guide-3.7
   migration-guide-4.[3-5]

.. note::
   | الإصدار التالي المخطط له هو **Zephyr 4.5**، ومن المستهدف إصداره في **أكتوبر 2026**.
   | تتوفر بالفعل المسودات الأولية لكل من :doc:`ملاحظات الإصدار <release-notes-4.5>`
     و:doc:`دليل الترحيل <migration-guide-4.5>`.

.. list-table::
    :header-rows: 1

    * - الإصدار
      - تاريخ الإصدار
      - نهاية الدعم
      - الحالة
      - الوثائق
    * - `Zephyr 4.4.0`_
      - 2026-04-14
      - 2027-04-12
      - أحدث إصدار مستقر
      - * :doc:`Release Notes <release-notes-4.4>`
        * :doc:`Migration Guide <migration-guide-4.4>`
    * - `Zephyr 4.3.0`_
      - 2025-11-14
      - 2026-10-15
      - مستقر
      - * :doc:`Release Notes <release-notes-4.3>`
        * :doc:`Migration Guide <migration-guide-4.3>`
    * - `Zephyr 3.7.0 (LTS3)`_
      - 2024-07-26
      - 2029-07-27
      - دعم طويل الأمد
      - * :doc:`Release Notes <release-notes-3.7>`
        * :doc:`Migration Guide <migration-guide-3.7>`

Previous LTS releases that have reached end-of-life:

+-------------------------+---------------+
| Release                 | EOL           |
+=========================+===============+
| `Zephyr 2.7.6 (LTS2)`_  | 2025-01-26    |
+-------------------------+---------------+
| `Zephyr 1.14.1 (LTS1)`_ | 2022-01-01    |
+-------------------------+---------------+

الإصدارات المنتهية
=====================

.. toctree::
   :hidden:
   :maxdepth: 1

   eol_releases

لم تعد الإصدارات المنتهية تخضع للصيانة ولا تتلقى إصلاحات أمنية. تتوفر ملاحظات
الإصدار وأدلة الترحيل الخاصة بها :ref:`هنا <eol_releases>`.

.. _zephyr_release_cycle:

دورة حياة الإصدار وصيانته
**********************************

الإصدارات الرئيسية وإصدارات الصيانة
===================================

يصدر Zephyr إصدارات رئيسية **كل ستة أشهر**، في أبريل وأكتوبر من كل عام. يوفر
هذا الجدول إصدارات منتظمة ومختبرة جيدًا دون إرباك المستخدمين بالتحديثات
المتكررة، مع مراعاة العطلات الرئيسية حول العالم.

تُنشر إصدارات الصيانة (النقطية) عند تراكم عدد كافٍ من الإصلاحات المهمة في فرع
الإصدار الرئيسي، من دون جدول زمني ثابت. ويخضع كل إصدار نقطي لدورة كاملة من
ضمان الجودة قبل نشره.

الدعم والصيانة طويلَا الأمد
=================================

تحظى الإصدارات المستقرة بالدعم خلال دورتَي إصدار (نحو عام واحد)، بينما يدعم
مشروع Zephyr بعض الإصدارات لفترة أطول، وتسمى إصدارات الدعم طويل الأمد (LTS).

يُنشر إصدار :ref:`الدعم طويل الأمد (LTS) <release_process_lts>` من Zephyr كل
سنتين ونصف إلى ثلاث سنوات، ويُصان في فرع مستقل عن الفرع الرئيسي لمدة تقارب
خمس سنوات بعد إصداره.

يوفر ذلك استقرارًا أكبر لمستخدمي المشروع ويمنحهم وقتًا أطول للترقية إلى إصدار
LTS التالي.


Transitioning to the new Release Cadence
========================================

The transition to the new release cadence will begin in 2026. Zephyr 4.4 is scheduled
for release in April 2026, and subsequent releases will occur every six months.

The projected timeline for upcoming releases is as follows:

+---------+-------------------+---------------------+
| Release | Planned Date      | Notes               |
+=========+===================+=====================+
| 4.4     | April 2026        |                     |
+---------+-------------------+---------------------+
| 4.5     | October 2026      |                     |
+---------+-------------------+---------------------+
| 4.6     | April 2027        | LTS4                |
+---------+-------------------+---------------------+
| 5.0     | October 2027      | Start of 5.x cycle  |
+---------+-------------------+---------------------+
| 5.1     | April 2028        |                     |
+---------+-------------------+---------------------+
| 5.2     | October 2028      |                     |
+---------+-------------------+---------------------+
| 5.3     | April 2029        |                     |
+---------+-------------------+---------------------+
| 5.4     | October 2029      | LTS5                |
+---------+-------------------+---------------------+

Starting with the 5.x release cycle, all releases will follow the new six-month
cadence from the beginning.


Security Fixes
==============

Each security issue fixed within Zephyr is backported or submitted to the
following releases:

- Currently supported Long Term Support (LTS) release.

- The most recent two releases.

For more information, see  :ref:`Security Vulnerability Reporting <reporting>`.

Release documentation
*********************

Each release includes two companion documents:

- Release notes summarize changes made across the project during the release cycle.
- Migration guides describe changes that require action when moving an application from one major
  release to the next.

Release Notes
=============

Release notes contain a list of changes that have been made to the different
areas of the project during the development cycle of the release.
Changes that require the user to modify their own application to support the new
release may be mentioned in the release notes, but the details regarding *what*
needs to be changed are to be detailed in the release's migration guide.

Updates to the release notes post release cycle is permitted but limited to
style, typographical fixes and to upmerge the notes from maintenance release
branches with the sole purpose of keeping the latest documentation consistent
with the changes in the project.

Migration Guides
================

Zephyr provides migration guides for all major releases, in order to assist
users transition from the previous release.

As mentioned in the previous section, changes in the code that require an action
(i.e. a modification of the source code or configuration files) on the part of
the user in order to keep the existing behavior of their application belong in
in the migration guide. This includes:

- Breaking API changes
- Deprecations
- Devicetree or Kconfig changes that affect the user (changes to defaults,
  renames, etc)
- Treewide changes that have an effect (e.g. changing the include path or
  defaulting to a different C standard library)
- Anything else that can affect the compilation or runtime behavior of an
  existing application

Each entry in the migration guide must include a brief explanation of the change
as well as refer to the Pull Request that introduced it, in order for the user
to be able to understand the context of the change.

.. _`GitHub repository`: https://github.com/zephyrproject-rtos/zephyr
.. _`GitHub tagged releases`: https://github.com/zephyrproject-rtos/zephyr/tags
.. _`Zephyr 1.14.1 (LTS1)`: https://docs.zephyrproject.org/1.14.1/
.. _`Zephyr 2.7.6 (LTS2)`: https://docs.zephyrproject.org/2.7.6/
.. _`Zephyr 3.7.0 (LTS3)`: https://docs.zephyrproject.org/3.7.0/
.. _`Zephyr 4.3.0`: https://docs.zephyrproject.org/4.3.0/
.. _`Zephyr 4.4.0`: https://docs.zephyrproject.org/4.4.0/
