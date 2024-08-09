# Awesome RunPod [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<p align="center">
  <img src="https://avatars.githubusercontent.com/u/95939477?s=200&v=4" alt="Awesome RunPod Logo" width="200" />
</p>

<p align="center">
  <strong>A curated list of amazing RunPod projects, libraries, and resources</strong>
</p>

<p align="center">
  <a href="https://github.com/kodxana/Awesome-RunPod/stargazers"><img src="https://img.shields.io/github/stars/kodxana/Awesome-RunPod?style=flat-square" alt="Stars Badge"/></a>
  <a href="https://github.com/kodxana/Awesome-RunPod/network/members"><img src="https://img.shields.io/github/forks/kodxana/Awesome-RunPod?style=flat-square" alt="Forks Badge"/></a>
  <a href="https://github.com/kodxana/Awesome-RunPod/pulls"><img src="https://img.shields.io/github/issues-pr/kodxana/Awesome-RunPod?style=flat-square" alt="Pull Requests Badge"/></a>
  <a href="https://github.com/kodxana/Awesome-RunPod/issues"><img src="https://img.shields.io/github/issues/kodxana/Awesome-RunPod?style=flat-square" alt="Issues Badge"/></a>
  <a href="https://github.com/kodxana/Awesome-RunPod/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/kodxana/Awesome-RunPod?style=flat-square"></a>
  <a href="https://github.com/kodxana/Awesome-RunPod/blob/master/LICENSE"><img src="https://img.shields.io/github/license/kodxana/Awesome-RunPod?style=flat-square" alt="License Badge"/></a>
</p>

## Contents

- [Tools](#tools)
- [Templates](#templates)
- [Serverless Workers](#serverless-workers)
- [Resources](#resources)
- [Video Tutorials](#video-tutorials)
- [Contributing](#contributing)

## Tools

| Tool                | Description                          | Author                                             | Stars |
|---------------------|--------------------------------------|----------------------------------------------------| ----- |
| [runpodctl]         | RunPod CLI for pod management        | [runpod](https://github.com/runpod)                | ![GitHub stars](https://img.shields.io/github/stars/runpod/runpodctl?style=social) |
| [runpod-python]     | Python library for RunPod API & SDK  | [runpod](https://github.com/runpod)                | ![GitHub stars](https://img.shields.io/github/stars/runpod/runpod-python?style=social) |

[runpodctl]: https://github.com/runpod/runpodctl
[runpod-python]: https://github.com/runpod/runpod-python

## Templates

| Template | Description | Author | Repository |
|----------|-------------|--------|------------|
| [Codecanvas] | The blank slate for your runpod, define your own dependencies and enjoy a machine with Jupyter, VSCode and Conda preinstalled. Environment survives reboots. | [Henk717] | No Github Repo
| [Codecanvas NPE] | Same as the above but without the persistent environment. | [Henk717] | No Github Repo |
| [EveryDream2] | General fine tuning for Stable Diffusion | [victorchall] | [![GitHub Repo](https://img.shields.io/badge/Repo-Github-brightgreen?style=flat-square&logo=github)](https://github.com/victorchall/EveryDream2trainer) ![GitHub stars](https://img.shields.io/github/stars/victorchall/EveryDream2trainer?style=social) |
| [InvokeAI] | A Stable Diffusion Toolkit | [invoke-ai] | [![GitHub Repo](https://img.shields.io/badge/Repo-Github-brightgreen?style=flat-square&logo=github)](https://github.com/invoke-ai/InvokeAI) ![GitHub stars](https://img.shields.io/github/stars/invoke-ai/InvokeAI?style=social) |
| [KoboldCpp] | A powerful GGUF based backend for Text Generation, Image Generation/Recognition and more. Comes bundled with the flexible KoboldAI Lite WebUI and KoboldAI/OpenAI API support.| [KoboldAI] | [![GitHub Repo](https://img.shields.io/badge/Repo-Github-brightgreen?style=flat-square&logo=github)](https://github.com/lostruins/koboldcpp) ![GitHub stars](https://img.shields.io/github/stars/lostruins/koboldcpp?style=social) |

[Codecanvas]: https://henk.tech/ccrunpod
[Codecanvas NPE]: https://henk.tech/ccnperunpod
[EveryDream2]: https://runpod.io/console/deploy?template=cpl3xoknjz&ref=vfker49t
[InvokeAI]: https://www.runpod.io/gsc?template=vm19ukkycf
[KoboldCpp]: https://koboldai.org/runpodcpp

[victorchall]: https://github.com/victorchall
[invoke-ai]: https://github.com/invoke-ai
[KoboldAI]: https://koboldai.com
[Henk717]: https://github.com/henk717

## Serverless Workers

| Worker | Description | Author | Repository |
|--------|-------------|--------|------------|
| [DreamBooth Worker] | RunPod Serverless worker for the DreamBooth endpoint | [runpod-workers] | [![GitHub Repo](https://img.shields.io/badge/Repo-Github-brightgreen?style=flat-square&logo=github)](https://github.com/runpod-workers/worker-dreambooth) ![GitHub stars](https://img.shields.io/github/stars/runpod-workers/worker-dreambooth?style=social) |
| [DeOldify worker] | RunPod Serverless worker for the restoration of old photos endpoint | [kodxana] | [![GitHub Repo](https://img.shields.io/badge/Repo-Github-brightgreen?style=flat-square&logo=github)](https://github.com/kodxana/worker-deoldify) ![GitHub stars](https://img.shields.io/github/stars/kodxana/worker-deoldify?style=social) |
| [Kandinsky Worker] | RunPod worker for the Kandinsky endpoint | [runpod-workers] | [![GitHub Repo](https://img.shields.io/badge/Repo-Github-brightgreen?style=flat-square&logo=github)](https://github.com/runpod-workers/worker-kandinsky) ![GitHub stars](https://img.shields.io/github/stars/runpod-workers/worker-kandinsky?style=social) |
| [RVC Serverless] | Simple RVC Serverless Endpoint for Runpod built upon Mangio-RVC-Fork | [chavinlo] | [![GitHub Repo](https://img.shields.io/badge/Repo-Github-brightgreen?style=flat-square&logo=github)](https://github.com/chavinlo/rvc-runpod) ![GitHub stars](https://img.shields.io/github/stars/chavinlo/rvc-runpod?style=social) |
| [Serverless GGML] | GGML Worker image for streaming predictions from large language models quantized with GGML | [OpenAccess-AI-Collective] | [![GitHub Repo](https://img.shields.io/badge/Repo-Github-brightgreen?style=flat-square&logo=github)](https://github.com/OpenAccess-AI-Collective/servereless-runpod-ggml) ![GitHub stars](https://img.shields.io/github/stars/OpenAccess-AI-Collective/servereless-runpod-ggml?style=social) |
| [Stable Diffusion v1 Worker] | RunPod worker for all Stable Diffusion v1 endpoints | [runpod-workers] | [![GitHub Repo](https://img.shields.io/badge/Repo-Github-brightgreen?style=flat-square&logo=github)](https://github.com/runpod-workers/worker-stable_diffusion_v1) ![GitHub stars](https://img.shields.io/github/stars/runpod-workers/worker-stable_diffusion_v1?style=social) |
| [Stable Diffusion v2 Worker] | RunPod worker for the Stable Diffusion v2 endpoints | [runpod-workers] | [![GitHub Repo](https://img.shields.io/badge/Repo-Github-brightgreen?style=flat-square&logo=github)](https://github.com/runpod-workers/worker-stable_diffusion_v2) ![GitHub stars](https://img.shields.io/github/stars/runpod-workers/worker-stable_diffusion_v2?style=social) |
| [Template Worker] | A simple worker that can be used as a starting point to build your own custom RunPod Endpoint API worker | [runpod-workers] | [![GitHub Repo](https://img.shields.io/badge/Repo-Github-brightgreen?style=flat-square&logo=github)](https://github.com/runpod-workers/worker-template) ![GitHub stars](https://img.shields.io/github/stars/runpod-workers/worker-template?style=social) |
| [Whisper Worker] | Whisper Worker for RunPod: Processing and transcribing audio with various Whisper models | [runpod-workers] | [![GitHub Repo](https://img.shields.io/badge/Repo-Github-brightgreen?style=flat-square&logo=github)](https://github.com/runpod-workers/worker-whisper) ![GitHub stars](https://img.shields.io/github/stars/runpod-workers/worker-whisper?style=social) |

[DreamBooth Worker]: https://github.com/runpod-workers/worker-dreambooth
[DeOldify worker]: https://github.com/kodxana/worker-deoldify
[Kandinsky Worker]: https://github.com/runpod-workers/worker-kandinsky
[RVC Serverless]: https://github.com/chavinlo/rvc-runpod
[Serverless GGML]: https://github.com/OpenAccess-AI-Collective/servereless-runpod-ggml
[Stable Diffusion v1 Worker]: https://github.com/runpod-workers/worker-stable_diffusion_v1
[Stable Diffusion v2 Worker]: https://github.com/runpod-workers/worker-stable_diffusion_v2
[Template Worker]: https://github.com/runpod-workers/worker-template
[Whisper Worker]: https://github.com/runpod-workers/worker-whisper

[runpod-workers]: https://github.com/runpod-workers
[kodxana]: https://github.com/kodxana
[chavinlo]: https://github.com/chavinlo
[OpenAccess-AI-Collective]: https://github.com/OpenAccess-AI-Collective
## Resources

| Resource                                  | Description                                  |
|-------------------------------------------|----------------------------------------------|
| [Getting Started with RunPod Serverless]  | Comprehensive guide to RunPod Serverless     |
| [RunPod Blog]                             | Official blog with tutorials and updates     |
| [RunPod Discord]                          | Community discussions and support            |
| [RunPod Documentation]                    | Official RunPod documentation                |

[Getting Started with RunPod Serverless]: https://trapdoor.cloud/getting-started-with-runpod-serverless/
[RunPod Blog]: https://blog.runpod.io/
[RunPod Discord]: https://discord.gg/cUpRmau42V
[RunPod Documentation]: https://docs.runpod.io/

## Video Tutorials

1. [Epic Web UI DreamBooth Update - New Best Settings](https://youtu.be/sRdtVanSRl4)
2. [Automatic1111 Stable Diffusion DreamBooth Guide](https://youtu.be/Tb4IYIYm4os)
3. [Training Midjourney Level Style Into SD 1.5 Model](https://youtu.be/m-UVVY_syP0)
4. [RunPod Fix For DreamBooth & xFormers](https://youtu.be/zA4LksIVas8)
5. [Ultimate RunPod Tutorial For Stable Diffusion](https://youtu.be/QN1vdGhjcRc)

## Contributing

Contributions are welcome! To add a project, template, or resource to the list:

1. Fork the repository
2. Create a new branch: `git checkout -b add-new-resource`
3. Add your resource to the appropriate section
4. Commit your changes: `git commit -am 'Add new resource'`
5. Push to the branch: `git push origin add-new-resource`
6. Submit a pull request

Alternatively, you can [open an issue](https://github.com/kodxana/Awesome-RunPod/issues/new) with the link and a brief description.

## License

Distributed under the MIT License. See `LICENSE` for more information.

---

<p align="center">
  <sub>If you find this list helpful, consider giving it a ⭐️ on GitHub!</sub>
</p>
