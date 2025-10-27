
F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install>.\python_embeded\python.exe -I ComfyUI\main.py --windows-standalone-build --highvram
[START] Security scan
[DONE] Security scan
## ComfyUI-Manager: installing dependencies done.
** ComfyUI startup time: 2025-10-27 19:47:58.892
** Platform: Windows
** Python version: 3.11.9 (tags/v3.11.9:de54cf5, Apr  2 2024, 10:12:12) [MSC v.1938 64 bit (AMD64)]
** Python executable: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\python_embeded\python.exe
** ComfyUI Path: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI
** ComfyUI Base Folder Path: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI
** User directory: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\user
** ComfyUI-Manager config path: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\user\default\ComfyUI-Manager\config.ini
** Log path: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\user\comfyui.log

Prestartup times for custom nodes:
   0.0 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\rgthree-comfy
   0.0 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\ComfyUI-Easy-Use
   9.5 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\comfyui-manager

Checkpoint files will always be loaded safely.
Total VRAM 12287 MB, total RAM 49075 MB
pytorch version: 2.8.0+cu128
Set vram state to: HIGH_VRAM
Device: cuda:0 NVIDIA GeForce RTX 3060 : cudaMallocAsync
Using pytorch attention
Python version: 3.11.9 (tags/v3.11.9:de54cf5, Apr  2 2024, 10:12:12) [MSC v.1938 64 bit (AMD64)]
ComfyUI version: 0.3.60
ComfyUI frontend version: 1.26.13
[Prompt Server] web root: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\python_embeded\Lib\site-packages\comfyui_frontend_package\static
[Crystools INFO] Crystools version: 1.27.3
[Crystools INFO] Platform release: 10
[Crystools INFO] JETSON: Not detected.
[Crystools INFO] CPU: AMD Ryzen 5 3600 6-Core Processor - Arch: AMD64 - OS: Windows 10
[Crystools INFO] pynvml (NVIDIA) initialized.
[Crystools INFO] GPU/s:
[Crystools INFO] 0) NVIDIA GeForce RTX 3060
[Crystools INFO] NVIDIA Driver: 581.57
[ComfyUI-Easy-Use] server: v1.3.4 Loaded
[ComfyUI-Easy-Use] web root: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\ComfyUI-Easy-Use\web_version/v2 Loaded
ComfyUI-GGUF: Allowing full torch compile
F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\python_embeded\Lib\site-packages\transparent_background\gui.py:24: UserWarning: Failed to import flet. Ignore this message when you do not need GUI mode.
  warnings.warn('Failed to import flet. Ignore this message when you do not need GUI mode.')
### Loading: ComfyUI-Manager (V3.37)
[ComfyUI-Manager] network_mode: public
### ComfyUI Version: v0.3.60 | Released on '2025-09-23'
======================================== ComfyUI-nunchaku Initialization ========================================
Nunchaku version: 1.0.0
ComfyUI-nunchaku version: 1.0.1
[ComfyUI-Manager] default cache updated: https://raw.githubusercontent.com/ltdrdata/ComfyUI-Manager/main/alter-list.json
[ComfyUI-Manager] default cache updated: https://raw.githubusercontent.com/ltdrdata/ComfyUI-Manager/main/model-list.json
[ComfyUI-Manager] default cache updated: https://raw.githubusercontent.com/ltdrdata/ComfyUI-Manager/main/github-stats.json
[ComfyUI-Manager] default cache updated: https://raw.githubusercontent.com/ltdrdata/ComfyUI-Manager/main/extension-node-map.json
Nodes `NunchakuPulidApply`,`NunchakuPulidLoader`, `NunchakuPuLIDLoaderV2` and `NunchakuFluxPuLIDApplyV2` import failed:
Traceback (most recent call last):
  File "F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\ComfyUI-nunchaku\__init__.py", line 77, in <module>
    from .nodes.models.pulid import (
  File "F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\ComfyUI-nunchaku\nodes\models\pulid.py", line 22, in <module>
    from nunchaku.pipeline.pipeline_flux_pulid import PuLIDPipeline
  File "F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\python_embeded\Lib\site-packages\nunchaku\pipeline\__init__.py", line 1, in <module>
    from .pipeline_flux_pulid import PuLIDFluxPipeline
  File "F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\python_embeded\Lib\site-packages\nunchaku\pipeline\pipeline_flux_pulid.py", line 18, in <module>
    import insightface
ModuleNotFoundError: No module named 'insightface'
[ComfyUI-Manager] default cache updated: https://raw.githubusercontent.com/ltdrdata/ComfyUI-Manager/main/custom-node-list.json
'nunchaku_versions.json' not found. Node will start in minimal mode.
=================================================================================================================
FantasyPortrait nodes not available due to error in importing them: No module named 'onnx'
------------------------------------------
Comfyroll Studio v1.76 :  175 Nodes Loaded
------------------------------------------
** For changes, please see patch notes at https://github.com/Suzie1/ComfyUI_Comfyroll_CustomNodes/blob/main/Patch_Notes.md
** For help, please see the wiki at https://github.com/Suzie1/ComfyUI_Comfyroll_CustomNodes/wiki
------------------------------------------
[F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\comfyui_controlnet_aux] | INFO -> Using ckpts path: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\comfyui_controlnet_aux\ckpts
[F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\comfyui_controlnet_aux] | INFO -> Using symlinks: False
[F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\comfyui_controlnet_aux] | INFO -> Using ort providers: ['CUDAExecutionProvider', 'DirectMLExecutionProvider', 'OpenVINOExecutionProvider', 'ROCMExecutionProvider', 'CPUExecutionProvider', 'CoreMLExecutionProvider']
DWPose: Onnxruntime with acceleration providers detected

Initializing ControlAltAI Nodes
Using pytorch attention
(RES4LYF) Init
(RES4LYF) Importing beta samplers.
(RES4LYF) Importing legacy samplers.

[rgthree-comfy] Loaded 48 fantastic nodes. 🎉

FETCH ComfyRegistry Data: 5/102
WAS Node Suite: OpenCV Python FFMPEG support is enabled
WAS Node Suite Warning: `ffmpeg_bin_path` is not set in `F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\was-node-suite-comfyui\was_suite_config.json` config file. Will attempt to use system ffmpeg binaries if available.
WAS Node Suite: Finished. Loaded 220 nodes successfully.

        "The only person you should try to be better than is the person you were yesterday." - Unknown


Import times for custom nodes:
   0.0 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\websocket_image_save.py
   0.0 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\canvas_tab
   0.0 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\ComfyUI_AdvancedRefluxControl
   0.0 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\qweneditutils
   0.0 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\comfyui-post-processing-nodes
   0.0 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\wlsh_nodes
   0.0 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\ComfyUI-TiledDiffusion
   0.0 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\comfyui-seamless-tiling
   0.0 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\janus-pro
   0.0 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\comfyui-inpaint-cropandstitch
   0.0 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\ComfyUI-GGUF
   0.0 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\teacache
   0.0 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\comfyui-omnigen
   0.0 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\controlaltai-nodes
   0.0 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\comfyui-kjnodes
   0.0 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\ComfyUI_Comfyroll_CustomNodes
   0.0 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\ComfyUI-LTXVideo
   0.1 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\rgthree-comfy
   0.1 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\ComfyUI_Sonic
   0.1 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\kaytool
   0.1 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\comfyui_controlnet_aux
   0.2 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\ComfyUI-WanVideoWrapper
   0.2 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\ComfyUI_Searge_LLM
   0.3 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\ComfyUI-ToSVG
   0.4 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\ComfyUI-Crystools
   0.4 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\ComfyUI-nunchaku
   0.4 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\comfyui-advancedliveportrait
   0.5 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\RES4LYF
   0.5 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\comfyui-kokoro
   0.5 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\comfyui-itools
   0.7 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\comfyui-videohelpersuite
   0.8 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\ComfyUI-Florence2
   0.9 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\comfyui-ollama
   1.1 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\comfyui-manager
   1.2 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\comfyui-inspyrenet-rembg
   1.7 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\was-node-suite-comfyui
   4.4 seconds: F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\ComfyUI-Easy-Use

Context impl SQLiteImpl.
Will assume non-transactional DDL.
No target revision found.
Starting server

To see the GUI go to: http://127.0.0.1:8188
FETCH ComfyRegistry Data: 10/102
FETCH ComfyRegistry Data: 15/102
FETCH ComfyRegistry Data: 20/102
FETCH ComfyRegistry Data: 25/102
FETCH ComfyRegistry Data: 30/102
FETCH ComfyRegistry Data: 35/102
FETCH ComfyRegistry Data: 40/102
FETCH ComfyRegistry Data: 45/102
FETCH ComfyRegistry Data: 50/102
FETCH ComfyRegistry Data: 55/102
FETCH ComfyRegistry Data: 60/102
FETCH ComfyRegistry Data: 65/102
FETCH ComfyRegistry Data: 70/102
FETCH ComfyRegistry Data: 75/102
FETCH ComfyRegistry Data: 80/102
FETCH ComfyRegistry Data: 85/102
FETCH ComfyRegistry Data: 90/102
FETCH ComfyRegistry Data: 95/102
FETCH ComfyRegistry Data: 100/102
FETCH ComfyRegistry Data [DONE]
[ComfyUI-Manager] default cache updated: https://api.comfy.org/nodes
FETCH DATA from: https://raw.githubusercontent.com/ltdrdata/ComfyUI-Manager/main/custom-node-list.json [DONE]
[ComfyUI-Manager] All startup tasks have been completed.
got prompt
Using pytorch attention in VAE
Using pytorch attention in VAE
VAE load device: cuda:0, offload device: cpu, dtype: torch.bfloat16
Using scaled fp8: fp8 matrix mult: False, scale input: False
CLIP/text encoder model load device: cuda:0, offload device: cpu, current: cpu, dtype: torch.float16
Requested to load WanVAE
0 models unloaded.
loaded completely 9.5367431640625e+25 242.02829551696777 True
Requested to load QwenImageTEModel_
loaded completely 9.5367431640625e+25 7909.737449645996 True
0 models unloaded.
Requested to load QwenImageTEModel_
loaded completely 9.5367431640625e+25 7909.737449645996 True
model weight dtype torch.bfloat16, manual cast: None
model_type FLUX
Enabling CPU offload
Total LoRAs in stack: 4
Requested to load NunchakuQwenImage
F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\ComfyUI-nunchaku\mixins\model.py:92: UserWarning: Skipping moving the model to GPU as offload is enabled
  warn("Skipping moving the model to GPU as offload is enabled", UserWarning)
  0%|                                                                                            | 0/6 [00:00<?, ?it/s]Composing 4 LoRAs...
F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\python_embeded\Lib\site-packages\nunchaku\lora\flux\utils.py:93: UserWarning: Using a non-tuple sequence for multidimensional indexing is deprecated and will be changed in pytorch 2.9; use x[tuple(seq)] instead of x[seq]. In pytorch 2.9 this will be interpreted as tensor index, x[torch.tensor(seq)], which will result either in an error or a different result (Triggered internally at C:\actions-runner\_work\pytorch\pytorch\pytorch\torch\csrc\autograd\python_variable_indexing.cpp:312.)
  result[[slice(0, extent) for extent in tensor.shape]] = tensor
Applied LoRA compositions to 480 modules.
LoRA composition (n=4) took 27310.8 ms
100%|████████████████████████████████████████████████████████████████████████████████████| 6/6 [01:07<00:00, 11.32s/it]
Requested to load WanVAE
0 models unloaded.
loaded completely 9.5367431640625e+25 242.02829551696777 True
Prompt executed in 155.49 seconds
got prompt
0 models unloaded.
Requested to load QwenImageTEModel_
loaded completely 9.5367431640625e+25 7909.737449645996 True
Requested to load WanVAE
0 models unloaded.
loaded completely 9.5367431640625e+25 242.02829551696777 True
Requested to load QwenImageTEModel_
loaded completely 9.5367431640625e+25 7909.737449645996 True
Requested to load NunchakuQwenImage
F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\ComfyUI-nunchaku\mixins\model.py:92: UserWarning: Skipping moving the model to GPU as offload is enabled
  warn("Skipping moving the model to GPU as offload is enabled", UserWarning)
100%|████████████████████████████████████████████████████████████████████████████████████| 6/6 [00:41<00:00,  6.98s/it]
Requested to load WanVAE
0 models unloaded.
loaded completely 9.5367431640625e+25 242.02829551696777 True
Prompt executed in 104.99 seconds
got prompt
Requested to load NunchakuQwenImage
100%|████████████████████████████████████████████████████████████████████████████████████| 6/6 [00:37<00:00,  6.20s/it]
Requested to load WanVAE
0 models unloaded.
loaded completely 9.5367431640625e+25 242.02829551696777 True
Prompt executed in 38.63 seconds
got prompt
Requested to load NunchakuQwenImage
100%|████████████████████████████████████████████████████████████████████████████████████| 6/6 [00:35<00:00,  5.94s/it]
Requested to load WanVAE
0 models unloaded.
loaded completely 9.5367431640625e+25 242.02829551696777 True
Prompt executed in 36.98 seconds
got prompt
Requested to load NunchakuQwenImage
100%|████████████████████████████████████████████████████████████████████████████████████| 6/6 [00:36<00:00,  6.01s/it]
Requested to load WanVAE
0 models unloaded.
loaded completely 9.5367431640625e+25 242.02829551696777 True
Prompt executed in 37.44 seconds
got prompt
0 models unloaded.
Requested to load QwenImageTEModel_
loaded completely 9.5367431640625e+25 7909.737449645996 True
Requested to load WanVAE
0 models unloaded.
loaded completely 9.5367431640625e+25 242.02829551696777 True
Requested to load QwenImageTEModel_
loaded completely 9.5367431640625e+25 7909.737449645996 True
Requested to load NunchakuQwenImage
F:\ComfyLatest\ComfyUI-Easy-Install\ComfyUI-Easy-Install\ComfyUI\custom_nodes\ComfyUI-nunchaku\mixins\model.py:92: UserWarning: Skipping moving the model to GPU as offload is enabled
  warn("Skipping moving the model to GPU as offload is enabled", UserWarning)
 50%|██████████████████████████████████████████                                          | 3/6 [00:21<00:20,  6.92s/it]