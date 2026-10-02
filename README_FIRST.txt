UntitledGame 0.0.0.1 - First Test Release
Windows x86-64

QUICK START

1. Extract all of UntitledGame.zip.
3. Double-click test.exe. 
4. See Manual0.0.0.1_en.pdf for the illustrated guide.

Character creation, playground battles, human control, and running existing
ONNX models do not require the optional Python training environment.

OPTIONAL BC / RL TRAINING

The rl_environment folder must be beside test.exe and keep that exact name.

Close the game before installing. In rl_environment, run ONE of:
  install_pinned.bat      CPU training; recommended if unsure.
  install_gpu_pinned.bat  NVIDIA CUDA training; check manual.

Internet access and enough disk space for Python and packages are required.
The CUDA environment uses significantly more disk space than the CPU environment.
Wait for a successful installation, then restart the game. The game checks
the environment before enabling the AI training menu. GPU training can be
selected only when the GPU check passes.

Do not rename rl_environment or copy someone else's .venv folder. The
installers create .venv locally. Run only one installer at a time, with the
game and any programs using this environment closed. 

SAVES AND BACKUPS

The game saves under your Windows user account, not inside the game folder:
  %APPDATA%\Godot\app_userdata\TestFlat\MyGame

Useful subfolders:
  saves\character_setups       Character saves
  saves\playground             Playground saves
  rl_model_saves\sessions      AI sessions and their training artifacts
  rl_model_saves\onnx          ONNX models and their JSON sidecars

Paste a path into File Explorer's address bar to open it. 

FEEDBACK

For a bug report or a feedback, please contact me.

LICENSES

See LICENSE_DECLARATION.md, THIRD_PARTY_NOTICES.md, and licenses/ for license
information. Third-party assets retain their own terms; this release does not
relicense them for standalone redistribution.

CONTACT

cchx7461@gmail.com
