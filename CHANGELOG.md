# 1.5.0
- Fixed TypeError in on_new event handler;
- Replaced deprecated set_syntax_file with assign_syntax for Sublime Text 4 compatibility;
- Added proper plugin_unloaded cleanup to stop worker thread on plugin reload;
- Removed Sublime Text 2 and Python 2 compatibility code;

# 1.4.0
- Automatically trim colons in keys if trim_leading_colon = true;

# 1.3.2
- Added new YAML syntax definition from https://github.com/sublimehq/Packages/pull/90;
- Fixed trimmed charracter;

# 1.3.1
- Added custom YAML syntax definition to support YAML keys with dashes and other non-alphanum symbols;

# 1.3.0
- Added workaround to avoid memory leak in ST3 (unfortunately with minor performance degradation);
- Restored ST2 compatibility;

# 1.2.0
- First tag is now automatically trimmed when symbol copied from localization file;
- Symbol list is now cached;
- Big refactoring;

# 1.1.0
- Added copy_yaml_symbol_to_clipboard command (thanks to nCore);
- Path now correctly updated after navigating to symbol;
- Minor fixes and refactoring;

# 1.0.0
Initial release.