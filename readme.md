git config --global user.email "trycloudai@gmail.com"

git config --global user.name "TryCloudAI"

git config --global core.editor "vim"

===

Q: + git clone https://github.com/google-research/meliad meliad_lib/meliad
fatal: destination path 'meliad_lib/meliad' already exists and is not an empty directory.
A: commit

Q: Python 3.10.9
A:
# Load pyenv automatically by appending
# the following to 
# ~/.bash_profile if it exists, otherwise ~/.profile (for login shells)
# and ~/.bashrc (for interactive shells) :

export PYENV_ROOT="$HOME/.pyenv"
[[ -d $PYENV_ROOT/bin ]] && export PATH="$PYENV_ROOT/bin:$PATH"
eval "$(pyenv init - bash)"

# Restart your shell for the changes to take effect.

# Load pyenv-virtualenv automatically by adding
# the following to ~/.bashrc:

eval "$(pyenv virtualenv-init -)"

Q: python -m tkinter
Traceback (most recent call last):
  File "/home/flame/.pyenv/versions/3.10.9/lib/python3.10/runpy.py", line 187, in _run_module_as_main
    mod_name, mod_spec, code = _get_module_details(mod_name, _Error)
  File "/home/flame/.pyenv/versions/3.10.9/lib/python3.10/runpy.py", line 146, in _get_module_details
    return _get_module_details(pkg_main_name, error)
  File "/home/flame/.pyenv/versions/3.10.9/lib/python3.10/runpy.py", line 110, in _get_module_details
    __import__(pkg_name)
  File "/home/flame/.pyenv/versions/3.10.9/lib/python3.10/tkinter/__init__.py", line 37, in <module>
    import _tkinter # If this fails your Python may not be configured for Tk
ModuleNotFoundError: No module named '_tkinter'



 

