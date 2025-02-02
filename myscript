#!/bin/bash

# This file will be sourced in init.sh

# https://raw.githubusercontent.com/ai-dock/comfyui/main/config/provisioning/default.sh

# Packages are installed after nodes so we can fix them...

APT_PACKAGES=(
    "unzip"
)

PIP_PACKAGES=(
    "torch==2.1.2"
    "torchvision==0.16.2"
)

NODES=(
    "https://github.com/ltdrdata/ComfyUI-Manager"
    "https://github.com/cubiq/ComfyUI_essentials"
    "https://github.com/chrisgoringe/cg-use-everywhere.git"
    "https://github.com/giriss/comfy-image-saver.git"
    "https://github.com/kaibioinfo/ComfyUI_AdvancedRefluxControl.git"
    "https://github.com/Suzie1/ComfyUI_Comfyroll_CustomNodes.git"
    "https://github.com/Fannovel16/comfyui_controlnet_aux.git"
    "https://github.com/madtunebk/ComfyUI-ControlnetAux.git"
    "https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet.git"
    "https://github.com/chflame163/ComfyUI_LayerStyle.git"
    "https://github.com/pythongosssss/ComfyUI-Custom-Scripts.git"
    "https://github.com/yolain/ComfyUI-Easy-Use.git"
    "https://github.com/marduk191/ComfyUI-Fluxpromptenhancer.git"
    "https://github.com/kijai/ComfyUI-KJNodes.git"
    "https://github.com/florestefano1975/comfyui-portrait-master.git"
    "https://github.com/jamesWalker55/comfyui-various.git"
    "https://github.com/WASasquatch/was-node-suite-comfyui.git"
    "https://github.com/SeargeDP/ComfyUI_Searge_LLM.git"
    "https://github.com/rgthree/rgthree-comfy.git"
    "https://github.com/KoreTeknology/ComfyUI-Universal-Styler.git"
    "https://github.com/un-seen/comfyui-tensorops.git"
    "https://github.com/gseth/ControlAltAI-Nodes.git"
    "https://github.com/ltdrdata/ComfyUI-Inspire-Pack.git"
    "https://github.com/Jonseed/ComfyUI-Detail-Daemon.git"
    "https://github.com/cubiq/ComfyUI_InstantID.git"
    "https://github.com/cubiq/PuLID_ComfyUI.git"
    "https://github.com/vuongminh1907/ComfyUI_ZenID.git"
    "https://github.com/cubiq/ComfyUI_IPAdapter_plus.git"
    "https://github.com/pythongosssss/ComfyUI-WD14-Tagger.git"
    "https://github.com/sipherxyz/comfyui-art-venture.git"
    "https://github.com/sipie800/ComfyUI-PuLID-Flux-Enhanced.git"
    "https://github.com/ltdrdata/ComfyUI-Impact-Pack.git"
    "https://github.com/crystian/ComfyUI-Crystools.git"
    "https://github.com/melMass/comfy_mtb.git"
    "https://github.com/Derfuu/Derfuu_ComfyUI_ModdedNodes.git"
    "https://github.com/MushroomFleet/DJZ-Nodes.git"
    "https://github.com/FizzleDorf/ComfyUI_FizzNodes.git"
    "https://github.com/XLabs-AI/x-flux-comfyui.git"
    "https://github.com/shadowcz007/comfyui-mixlab-nodes.git"
    "https://github.com/kijai/ComfyUI-Florence2.git"
)

CHECKPOINT_MODELS=(
    "https://huggingface.co/runwayml/stable-diffusion-v1-5/resolve/main/v1-5-pruned-emaonly.ckpt"
    "https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/resolve/main/sd_xl_base_1.0.safetensors"
    "https://huggingface.co/stabilityai/stable-diffusion-xl-refiner-1.0/resolve/main/sd_xl_refiner_1.0.safetensors"
)

DIFFUSION_MODELS=(
    "https://huggingface.co/black-forest-labs/FLUX.1-Canny-dev/resolve/main/flux1-canny-dev.safetensors"
    "https://huggingface.co/black-forest-labs/FLUX.1-Depth-dev/resolve/main/flux1-depth-dev.safetensors"
    "https://huggingface.co/black-forest-labs/FLUX.1-Fill-dev/resolve/main/flux1-fill-dev.safetensors"
)

UNET_MODELS=(
    "https://huggingface.co/black-forest-labs/FLUX.1-dev/resolve/main/flux1-dev.safetensors"
)

LORA_MODELS=(
    "https://huggingface.co/black-forest-labs/FLUX.1-Canny-dev-lora/resolve/main/flux1-canny-dev-lora.safetensors"
    "https://huggingface.co/black-forest-labs/FLUX.1-Depth-dev-lora/resolve/main/flux1-depth-dev-lora.safetensors"
)

VAE_MODELS=(
    "https://huggingface.co/stabilityai/sd-vae-ft-ema-original/resolve/main/vae-ft-ema-560000-ema-pruned.safetensors"
    "https://huggingface.co/stabilityai/sd-vae-ft-mse-original/resolve/main/vae-ft-mse-840000-ema-pruned.safetensors"
    "https://huggingface.co/stabilityai/sdxl-vae/resolve/main/sdxl_vae.safetensors"
    "https://huggingface.co/black-forest-labs/FLUX.1-schnell/resolve/main/ae.safetensors"
)

CLIP_MODELS=(
    "https://huggingface.co/comfyanonymous/flux_text_encoders/resolve/main/clip_l.safetensors"
    "https://huggingface.co/comfyanonymous/flux_text_encoders/resolve/main/t5xxl_fp16.safetensors"
    "https://huggingface.co/QuanSun/EVA-CLIP/resolve/main/EVA02_CLIP_L_336_psz14_s6B.pt"
)

CLIP_VISION_MODELS=(
    "https://huggingface.co/comfyanonymous/clip_vision_g/resolve/main/clip_vision_g.safetensors"
    "https://huggingface.co/Comfy-Org/sigclip_vision_384/resolve/main/sigclip_vision_patch14_384.safetensors"
    "https://huggingface.co/openai/clip-vit-large-patch14/resolve/main/model.safetensors"
)

CONTROLNET_MODELS=(
    "https://huggingface.co/lllyasviel/sd_control_collection/resolve/main/diffusers_xl_canny_mid.safetensors"
    "https://huggingface.co/lllyasviel/sd_control_collection/resolve/main/diffusers_xl_depth_mid.safetensors"
    "https://huggingface.co/lllyasviel/sd_control_collection/resolve/main/t2i-adapter_diffusers_xl_openpose.safetensors"
    "https://huggingface.co/webui/ControlNet-modules-safetensors/resolve/main/control_canny-fp16.safetensors"
    "https://huggingface.co/kohya-ss/ControlNet-diff-modules/resolve/main/diff_control_sd15_depth_fp16.safetensors"
    "https://huggingface.co/webui/ControlNet-modules-safetensors/resolve/main/control_openpose-fp16.safetensors"
    "https://huggingface.co/webui/ControlNet-modules-safetensors/resolve/main/t2iadapter_canny-fp16.safetensors"
    "https://huggingface.co/webui/ControlNet-modules-safetensors/resolve/main/t2iadapter_openpose-fp16.safetensors"
    "https://huggingface.co/XLabs-AI/flux-controlnet-collections/resolve/main/flux-canny-controlnet-v3.safetensors"
    "https://huggingface.co/XLabs-AI/flux-controlnet-collections/resolve/main/flux-canny-controlnet_v2.safetensors"
    "https://huggingface.co/XLabs-AI/flux-controlnet-collections/resolve/main/flux-depth-controlnet-v3.safetensors"
    "https://huggingface.co/XLabs-AI/flux-controlnet-collections/resolve/main/flux-hed-controlnet-v3.safetensors"
    "https://huggingface.co/XLabs-AI/flux-controlnet-collections/resolve/main/flux-hed-controlnet.safetensors"
)

IPADAPTER_MODELS=(
    "https://huggingface.co/XLabs-AI/flux-ip-adapter/resolve/main/ip_adapter.safetensors"
)

LLM_MODELS=(
    "https://huggingface.co/MaziyarPanahi/Mistral-7B-Instruct-v0.3-GGUF/resolve/main/Mistral-7B-Instruct-v0.3.Q8_0.gguf"
)

PULID_MODELS=(
    "https://huggingface.co/guozinan/PuLID/resolve/main/pulid_flux_v0.9.0.safetensors"
    "https://huggingface.co/guozinan/PuLID/resolve/main/pulid_flux_v0.9.1.safetensors"
)

STYLE_MODELS=(
    "https://huggingface.co/black-forest-labs/FLUX.1-Redux-dev/resolve/main/flux1-redux-dev.safetensors"
)

### DO NOT EDIT BELOW HERE UNLESS YOU KNOW WHAT YOU ARE DOING ###

function provisioning_start() {
    if [[ ! -d /opt/environments/python ]]; then 
        export MAMBA_BASE=true
    fi
    source /opt/ai-dock/etc/environment.sh
    source /opt/ai-dock/bin/venv-set.sh comfyui

    provisioning_print_header
    provisioning_get_apt_packages
    provisioning_get_nodes
    provisioning_get_pip_packages
    
    # Existing model categories
    provisioning_get_models "${WORKSPACE}/storage/stable_diffusion/models/ckpt" "${CHECKPOINT_MODELS[@]}"
    provisioning_get_models "${WORKSPACE}/storage/stable_diffusion/models/unet" "${UNET_MODELS[@]}"
    provisioning_get_models "${WORKSPACE}/storage/stable_diffusion/models/lora" "${LORA_MODELS[@]}"
    provisioning_get_models "${WORKSPACE}/storage/stable_diffusion/models/controlnet" "${CONTROLNET_MODELS[@]}"
    provisioning_get_models "${WORKSPACE}/storage/stable_diffusion/models/vae" "${VAE_MODELS[@]}"
    
    # New model categories
    provisioning_get_models "${WORKSPACE}/ComfyUI/models/diffusion_models" "${DIFFUSION_MODELS[@]}"
    provisioning_get_models "${WORKSPACE}/ComfyUI/models/clip" "${CLIP_MODELS[@]}"
    provisioning_get_models "${WORKSPACE}/ComfyUI/models/clip_vision" "${CLIP_VISION_MODELS[@]}"
    provisioning_get_models "${WORKSPACE}/ComfyUI/models/ipadapter" "${IPADAPTER_MODELS[@]}"
    provisioning_get_models "${WORKSPACE}/ComfyUI/models/llm_gguf" "${LLM_MODELS[@]}"
    provisioning_get_models "${WORKSPACE}/ComfyUI/models/pulid" "${PULID_MODELS[@]}"
    provisioning_get_models "${WORKSPACE}/ComfyUI/models/style_models" "${STYLE_MODELS[@]}"
    
    # Handle InsightFace models
    provisioning_get_models "/tmp" "https://huggingface.co/MonsterMMORPG/tools/resolve/main/antelopev2.zip"
    mkdir -p "${WORKSPACE}/ComfyUI/models/insightface/models"
    unzip /tmp/antelopev2.zip -d "${WORKSPACE}/ComfyUI/models/insightface/models/"
    rm /tmp/antelopev2.zip

    provisioning_print_end
}

function pip_install() {
    if [[ -z $MAMBA_BASE ]]; then
            "$COMFYUI_VENV_PIP" install --no-cache-dir "$@"
        else
            micromamba run -n comfyui pip install --no-cache-dir "$@"
        fi
}

function provisioning_get_apt_packages() {
    if [[ -n $APT_PACKAGES ]]; then
            sudo $APT_INSTALL ${APT_PACKAGES[@]}
    fi
}

function provisioning_get_pip_packages() {
    if [[ -n $PIP_PACKAGES ]]; then
            pip_install ${PIP_PACKAGES[@]}
    fi
}

function provisioning_get_nodes() {
    for repo in "${NODES[@]}"; do
        dir="${repo##*/}"
        path="/opt/ComfyUI/custom_nodes/${dir}"
        requirements="${path}/requirements.txt"
        if [[ -d $path ]]; then
            if [[ ${AUTO_UPDATE,,} != "false" ]]; then
                printf "Updating node: %s...\n" "${repo}"
                ( cd "$path" && git pull )
                if [[ -e $requirements ]]; then
                   pip_install -r "$requirements"
                fi
            fi
        else
            printf "Downloading node: %s...\n" "${repo}"
            git clone "${repo}" "${path}" --recursive
            if [[ -e $requirements ]]; then
                pip_install -r "${requirements}"
            fi
        fi
    done
}

function provisioning_get_default_workflow() {
    if [[ -n $DEFAULT_WORKFLOW ]]; then
        workflow_json=$(curl -s "$DEFAULT_WORKFLOW")
        if [[ -n $workflow_json ]]; then
            echo "export const defaultGraph = $workflow_json;" > /opt/ComfyUI/web/scripts/defaultGraph.js
        fi
    fi
}

function provisioning_get_models() {
    if [[ -z $2 ]]; then return 1; fi
    
    dir="$1"
    mkdir -p "$dir"
    shift
    arr=("$@")
    printf "Downloading %s model(s) to %s...\n" "${#arr[@]}" "$dir"
    for url in "${arr[@]}"; do
        printf "Downloading: %s\n" "${url}"
        provisioning_download "${url}" "${dir}"
        printf "\n"
    done
}

function provisioning_print_header() {
    printf "\n##############################################\n#                                            #\n#          Provisioning container            #\n#                                            #\n#         This will take some time           #\n#                                            #\n# Your container will be ready on completion #\n#                                            #\n##############################################\n\n"
    if [[ $DISK_GB_ALLOCATED -lt $DISK_GB_REQUIRED ]]; then
        printf "WARNING: Your allocated disk size (%sGB) is below the recommended %sGB - Some models will not be downloaded\n" "$DISK_GB_ALLOCATED" "$DISK_GB_REQUIRED"
    fi
}

function provisioning_print_end() {
    printf "\nProvisioning complete:  Web UI will start now\n\n"
}

function provisioning_has_valid_hf_token() {
    [[ -n "$HF_TOKEN" ]] || return 1
    url="https://huggingface.co/api/whoami-v2"

    response=$(curl -o /dev/null -s -w "%{http_code}" -X GET "$url" \
        -H "Authorization: Bearer $HF_TOKEN" \
        -H "Content-Type: application/json")

    if [ "$response" -eq 200 ]; then
        return 0
    else
        return 1
    fi
}

function provisioning_has_valid_civitai_token() {
    [[ -n "$CIVITAI_TOKEN" ]] || return 1
    url="https://civitai.com/api/v1/models?hidden=1&limit=1"

    response=$(curl -o /dev/null -s -w "%{http_code}" -X GET "$url" \
        -H "Authorization: Bearer $CIVITAI_TOKEN" \
        -H "Content-Type: application/json")

    if [ "$response" -eq 200 ]; then
        return 0
    else
        return 1
    fi
}

function provisioning_download() {
    if [[ -n $HF_TOKEN && $1 =~ ^https://([a-zA-Z0-9_-]+\.)?huggingface\.co(/|$|\?) ]]; then
        auth_token="$HF_TOKEN"
    elif [[ -n $CIVITAI_TOKEN && $1 =~ ^https://([a-zA-Z0-9_-]+\.)?civitai\.com(/|$|\?) ]]; then
        auth_token="$CIVITAI_TOKEN"
    fi
    
    if [[ -n $auth_token ]]; then
        wget --header="Authorization: Bearer $auth_token" -qnc --content-disposition --show-progress -e dotbytes="${3:-4M}" -P "$2" "$1"
    else
        wget -qnc --content-disposition --show-progress -e dotbytes="${3:-4M}" -P "$2" "$1"
    fi
}

provisioning_start
