Change Log
==========

Version 0.2.4
^^^^^^^^^^^^^
- Released on 18 April 2016
- Added better logging

Version 0.2.3
^^^^^^^^^^^^^
- Released on 25 May 2016
- Added ``chunky show`` subcommand
- Restructured the subcommand system so it uses argparse from the beginning
- Added feature to ``confgure`` to output a blank configuration
- Removed ``__init__`` from ``list`` output
- Added ``dependencies()`` to the Pipeline class
- ``install`` attempts to pip install pipeline depencencies, as returned by ``depencencies()``