ufws (UnFuck Windows Setup)
===========================
**ufws** (imagine being drunk beyond all fuck and attempting to say _oops_)
is a simple script to bypass Windows 11 system requirements when upgrading from
Windows 10. For clean installation bypass check `alternative_bypass.md`.

**ufws** is meant to be used with an unmodified installation media. Any issues
caused by usage of a modified installation media will be ignored.

Usage
-----
**ufws** can be used in two ways. You can run it from an administrative command
prompt or directly.

### Running directly
Place **ufws** in the root of the installation media and run it as an
administrator. It will detect the path and automatically start the setup wizard.

### Running from administrative command prompt
```
ufws.cmd <install_source_path> [param1] [param2] ...
```

#### Examples
```
ufws.cmd E:
ufws.cmd D:\extracted_iso
ufws.cmd E: /Console
ufws.cmd E: /Pkey XXXXX-XXXXX-XXXXX-XXXXX-XXXXX /Console
```

License
-------
This script is licensed under the terms of the GNU General Public License v3.0
