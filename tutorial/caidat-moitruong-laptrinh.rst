##########################################################################################################
Cài đặt môi trường lập trình cho ngôn ngữ reStructuredText với Atom Editor trên hệ điều hành Ubuntu 16.04
##########################################################################################################

* **Thực hiện:** `Thi Minh Nhựt <https://github.com/thiminhnhut>`_ - **Email:** `thiminhnhut\@gmail.com <thiminhnhut@gmail.com>`_

* **Thời gian:** Ngày 10 tháng 10 năm 2017

Nguồn tham khảo
****************

* `Atom Package <https://atom.io/packages>`_

Nội dung hướng dẫn
*******************

Cài đặt môi trường lập trình cho ngôn ngữ reStructuredText với Atom Editor trên hệ điều hành Ubuntu 16.04
==========================================================================================================

* Cài đặt `Atom Editor <https://atom.io/>`_.

  - Chọn phiên bản thích hợp với hệ điều hành, ví dụ file ``atom-amd64.deb``.

  - Cài đặt ``Atom``::

      $ sudo dpkg -i atom-amd64.deb

* Cài đặt các packages sau (trên ``Atom`` và trên hệ điều hành ``Ubuntu``):

  - ``Atom packages``: `rst-preview-pandoc <https://atom.io/packages/rst-preview-pandoc>`_ và `language-restructuredtext <https://atom.io/packages/language-restructuredtext>`_.

    + `rst-preview-pandoc (reStructuredText Preview package) <https://atom.io/packages/rst-preview-pandoc>`_: Open a pandoc-rendered version of the Markdown in the current editor with ``ctrl-shift-e``. This is a fork of markdown-preview-pandoc package. This package can read reStructuredText for Sphinx, too. This package needs ``pandoc`` library and ``language-reStructuredText`` package.

    + `language-restructuredtext (reStructuredText language support in Atom) <https://atom.io/packages/language-restructuredtext>`_: Add snippets and syntax highlighting for reStructuredText files.

  - ``Ubuntu packages`` với thư viện `pandoc <https://pandoc.org/>`_::

    $ sudo apt-get install -y pandoc

Cách xem nội dung tài liệu viết bằng ngôn ngữ reStructuredText
===============================================================

* Sử dụng tổ hợp phím ``Ctrl + Shift + E`` để xem trước nội dung của tài liệu.
