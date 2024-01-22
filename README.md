[![Travis Build Status](https://api.travis-ci.org/bulletphysics/bullet3.png?branch=master)](https://travis-ci.org/bulletphysics/bullet3)
[![Appveyor Build status](https://ci.appveyor.com/api/projects/status/6sly9uxajr6xsstq)](https://ci.appveyor.com/project/erwincoumans/bullet3)

# Bullet Physics SDK
这是 Bullet 物理 SDK 的官方 C++ 源代码存储库：用于 VR、游戏、视觉效果、机器人、机器学习等的实时碰撞检测和多物理模拟。
This is the official C++ source code repository of the Bullet Physics SDK: real-time collision detection and multi-physics simulation for VR, games, visual effects, robotics, machine learning etc.

![PyBullet](https://pybullet.org/wordpress/wp-content/uploads/2019/03/cropped-pybullet.png)


Bullet Physics SDK，特别是Bullet3，是一个广泛使用的开源物理模拟库，用于实时模拟三维物理现象，如碰撞检测、刚体和软体动力学、约束解决等。Bullet3是Bullet Physics的最新版本，它提供了更加模块化、可扩展和高效的功能。以下是Bullet3的详细介绍：

### 主要特点：

1. **开源和跨平台**：Bullet3是开源的，并且支持Windows、Linux、macOS等多个操作系统，使其能够轻松集成到各种项目中。
2. **实时性能**：Bullet3设计用于实时应用，如游戏和VR，它能够在高帧率下模拟复杂的物理交互。
3. **多物理模拟**：Bullet3支持刚体动力学、软体动力学、粒子动力学、布料模拟、流体模拟等多种物理模拟类型。
4. **碰撞检测**：Bullet3提供了高效的碰撞检测算法，能够处理大量的动态和静态物体之间的碰撞。
5. **约束和关节**：Bullet3可以模拟各种约束和关节，如铰链、滑轮、球形关节等，使物体能够按照真实世界的方式相互连接和移动。
6. **车辆动力学**：Bullet3内置了车辆动力学模拟，可以模拟汽车的悬挂系统、轮胎摩擦等。
7. **可扩展性**：Bullet3的模块化设计使其易于扩展和定制。用户可以根据需要添加自己的物理模型、碰撞形状或求解器。
8. **图形界面**：虽然Bullet3本身是一个物理引擎，不包含图形渲染功能，但它可以与各种图形引擎（如OpenGL、DirectX、Vulkan等）无缝集成。
9. **与机器学习集成**：Bullet3的数据结构和API使其适合与机器学习算法结合，用于物理预测、控制等任务。
10. **社区支持**：Bullet3有一个活跃的开发者社区，提供了大量的教程、示例和问题解决支持。

### 应用领域：

* **游戏开发**：Bullet3是游戏开发中最流行的物理引擎之一，用于模拟角色动作、物体碰撞、车辆行为等。
* **虚拟现实（VR）**：在VR应用中，Bullet3提供了真实的物理交互，增强了用户的沉浸感。
* **视觉效果（VFX）**：在电影和动画制作中，Bullet3用于模拟逼真的物理现象，如爆炸、破碎、流体等。
* **机器人技术**：Bullet3的实时物理模拟功能使其在机器人运动规划和控制中具有重要应用。
* **机器学习**：Bullet3可用于生成物理模拟数据，训练机器学习模型以预测和控制物理系统。

总的来说，Bullet3是一个功能强大、灵活且易于集成的物理模拟库，适用于多个领域，从游戏开发到机器人技术。

<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p dir="auto"><a href="https://travis-ci.org/bulletphysics/bullet3" rel="nofollow"><img src="https://camo.githubusercontent.com/330aef994e1f84c37fb8c014ef377eb897e49f4b13a9fa9fd9f5c0f657bba708/68747470733a2f2f6170692e7472617669732d63692e6f72672f62756c6c6574706879736963732f62756c6c6574332e706e673f6272616e63683d6d6173746572" alt="特拉维斯构建状态" data-canonical-src="https://api.travis-ci.org/bulletphysics/bullet3.png?branch=master" style="max-width: 100%;"></a>
<a href="https://ci.appveyor.com/project/erwincoumans/bullet3" rel="nofollow"><img src="https://camo.githubusercontent.com/d487fc7d5b6e3e32876bdced49feab0459e5760e358971239f53ded2d684cc93/68747470733a2f2f63692e6170707665796f722e636f6d2f6170692f70726f6a656374732f7374617475732f36736c79397578616a72367873737471" alt="Appveyor构建状态" data-canonical-src="https://ci.appveyor.com/api/projects/status/6sly9uxajr6xsstq" style="max-width: 100%;"></a></p>
<h1 tabindex="-1" dir="auto"><a id="user-content-bullet-physics-sdk" class="anchor" aria-hidden="true" tabindex="-1" href="#bullet-physics-sdk"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">子弹物理 SDK</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是 Bullet 物理 SDK 的官方 C++ 源代码存储库：用于 VR、游戏、视觉效果、机器人、机器学习等的实时碰撞检测和多物理模拟。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/e7a277edc47daf1ac24b5b14a8c8eff8e34b67a50771af54e10303ebd5e9c0dd/68747470733a2f2f707962756c6c65742e6f72672f776f726470726573732f77702d636f6e74656e742f75706c6f6164732f323031392f30332f63726f707065642d707962756c6c65742e706e67"><img src="https://camo.githubusercontent.com/e7a277edc47daf1ac24b5b14a8c8eff8e34b67a50771af54e10303ebd5e9c0dd/68747470733a2f2f707962756c6c65742e6f72672f776f726470726573732f77702d636f6e74656e742f75706c6f6164732f323031392f30332f63726f707065642d707962756c6c65742e706e67" alt="pybullet" data-canonical-src="https://pybullet.org/wordpress/wp-content/uploads/2019/03/cropped-pybullet.png" style="max-width: 100%;"></a></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-issues" class="anchor" aria-hidden="true" tabindex="-1" href="#issues"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">问题</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">问题跟踪器充斥着支持问题，在清理之前会关闭。</font><font style="vertical-align: inherit;">使用</font></font><a href="http://pybullet.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PyBullet 论坛</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与其他人讨论。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-pybullet" class="anchor" aria-hidden="true" tabindex="-1" href="#pybullet"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pybullet</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">强烈建议使用 PyBullet Python 绑定来改进对机器人、强化学习和 VR 的支持。</font><font style="vertical-align: inherit;">使用 pip install pybullet 并查看</font></font><a href="https://docs.google.com/document/d/10sXEhzFRSnvFcl3XxNGhnD4N2SedqwdAvK3dsihxVUA/edit#heading=h.2ye70wns7io3" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PyBullet 快速入门指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装很简单：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>pip3 install pybullet --upgrade --user
python3 -m pybullet_envs.examples.enjoy_TF_AntBulletEnv_v0_2017may
python3 -m pybullet_envs.examples.enjoy_TF_HumanoidFlagrunHarderBulletEnv_v1_2017jul
python3 -m pybullet_envs.deep_mimic.testrl --arg_file run_humanoid3d_backflip_args.txt
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip3 install pybullet --upgrade --user
python3 -m pybullet_envs.examples.enjoy_TF_AntBulletEnv_v0_2017may
python3 -m pybullet_envs.examples.enjoy_TF_HumanoidFlagrunHarderBulletEnv_v1_2017jul
python3 -m pybullet_envs.deep_mimic.testrl --arg_file run_humanoid3d_backflip_args.txt" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您在研究中使用 PyBullet，请像这样引用它：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>@MISC{coumans2021,
author =   {Erwin Coumans and Yunfei Bai},
title =    {PyBullet, a Python module for physics simulation for games, robotics and machine learning},
howpublished = {\url{http://pybullet.org}},
year = {2016--2021}
}
</code></pre><div class="zeroclipboard-container">

  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-requirements-for-bullet-physics-c" class="anchor" aria-hidden="true" tabindex="-1" href="#requirements-for-bullet-physics-c"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">子弹物理 C++ 的要求</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于 C++ 2003 的 C++ 编译器。该库在 Windows、Linux、Mac OSX、iOS、Android 上进行了测试，但应该可以在任何具有 C++ 编译器的平台上运行。</font><font style="vertical-align: inherit;">一些可选演示需要 OpenGL 2 或 OpenGL 3，还有一些非图形演示和单元测试。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-contributors-and-coding-style-information" class="anchor" aria-hidden="true" tabindex="-1" href="#contributors-and-coding-style-information"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献者和编码风格信息</font></font></h2>
<p dir="auto"><a href="https://docs.google.com/document/d/1u9vyzPtrVoVhYqQOGNWUgjRbfwfCdIts_NzmvgiJ144/edit" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://docs.google.com/document/d/1u9vyzPtrVoVhYqQOGNWUgjRbfwfCdIts_NzmvgiJ144/edit</font></font></a></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-requirements-for-experimental-opencl-gpgpu-support" class="anchor" aria-hidden="true" tabindex="-1" href="#requirements-for-experimental-opencl-gpgpu-support"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实验性 OpenCL GPGPU 支持的要求</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">整个碰撞检测和刚体动力学都可以在 GPU 上执行。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高端桌面 GPU，例如 AMD Radeon 7970 或 NVIDIA GTX 680 或更好。</font><font style="vertical-align: inherit;">我们在 Windows、Linux 和 Mac OSX 下成功测试了该软件。</font><font style="vertical-align: inherit;">该软件目前无法在 OpenCL CPU 设备上运行。</font><font style="vertical-align: inherit;">它可能在笔记本电脑 GPU 上运行，但性能可能不会很好。</font><font style="vertical-align: inherit;">请注意，OpenCL 驱动程序通常无法编译内核。</font><font style="vertical-align: inherit;">存在一些单元测试来追踪问题，但需要做更多的工作来覆盖所有 OpenCL 内核。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-license" class="anchor" aria-hidden="true" tabindex="-1" href="#license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有源代码文件均根据宽松的 zlib 许可证 ( </font></font><a href="http://opensource.org/licenses/Zlib" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://opensource.org/licenses/Zlib</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ) 获得许可，除非在特定文件夹/文件中进行了不同标记。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-build-instructions-for-bullet-using-vcpkg" class="anchor" aria-hidden="true" tabindex="-1" href="#build-instructions-for-bullet-using-vcpkg"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 vcpkg 构建 Bullet 的说明</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以使用</font></font><a href="https://github.com/Microsoft/vcpkg/"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">vcpkg</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">依赖项管理器下载并安装 Bullet：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>git clone https://github.com/Microsoft/vcpkg.git
cd vcpkg
./bootstrap-vcpkg.sh
./vcpkg integrate install
./vcpkg install bullet3
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://github.com/Microsoft/vcpkg.git
cd vcpkg
./bootstrap-vcpkg.sh
./vcpkg integrate install
./vcpkg install bullet3" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">vcpkg 中的 Bullet 端口由 Microsoft 团队成员和社区贡献者保持最新。</font><font style="vertical-align: inherit;">如果版本已过时，请</font><font style="vertical-align: inherit;">在 vcpkg 存储库上</font></font><a href="https://github.com/Microsoft/vcpkg"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建问题或拉取请求。</font></font></a><font style="vertical-align: inherit;"></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-build-instructions-for-bullet-using-premake-you-can-also-use-cmake-instead" class="anchor" aria-hidden="true" tabindex="-1" href="#build-instructions-for-bullet-using-premake-you-can-also-use-cmake-instead"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 premake 构建 Bullet 的说明。</font><font style="vertical-align: inherit;">您也可以使用 cmake 代替。</font></font></h2>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">视窗</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单击 build_visual_studio_vr_pybullet_double.bat 并打开 build3/vs2010/0_Bullet3Solution.sln 当系统询问时，将项目转换为较新版本的 Visual Studio。</font><font style="vertical-align: inherit;">如果您将 Python 安装在 C:\ 根目录中，则批处理文件应该会自动找到它。</font><font style="vertical-align: inherit;">否则，编辑此批处理文件以选择 Python include/lib 目录所在的位置。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">适用于 HTC Vive 和 Oculus Rift 的 Windows 虚拟现实沙盒</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建并运行 App_SharedMemoryPhysics_VR 项目，最好在发布/优化构建中。</font><font style="vertical-align: inherit;">您可以使用以下命令从 Python pybullet 连接到沙箱：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>import pybullet as p
p.connect(p.SHARED_MEMORY) #or (p.TCP, "localhost", 6667) or (p.UDP, "192.168.86.10",1234)
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="import pybullet as p
p.connect(p.SHARED_MEMORY) #or (p.TCP, &quot;localhost&quot;, 6667) or (p.UDP, &quot;192.168.86.10&quot;,1234)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux 和 Mac OSX gnu make</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确保安装了 gcc 和 cmake（</font></font><code>sudo apt-get install build-essential</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于</font></font><code>sudo apt-get install cmake</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Linux、</font></font><code>brew install cmake</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mac 或</font></font><a href="https://cmake.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://cmake.org</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在终端类型中：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>./build_cmake_pybullet_double.sh
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./build_cmake_pybullet_double.sh" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该脚本将调用 cmake 并在 build_cmake 目录中构建。</font><font style="vertical-align: inherit;">你可以在 Bullet/examples/pybullet 中找到 pybullet。</font><font style="vertical-align: inherit;">BulletExampleBrowser 二进制文件将位于 Bullet/examples/ExampleBrowser 中。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以使用 premake 构建 Bullet。</font><font style="vertical-align: inherit;">build3 文件夹中有预制可执行文件。</font><font style="vertical-align: inherit;">根据您的系统（Linux 32 位、64 位或 Mac OSX），使用以下行之一使用 premake：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>cd build3
./premake4_linux --double gmake
./premake4_linux64 --double gmake
./premake4_osx --double --enable_pybullet gmake
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="cd build3
./premake4_linux --double gmake
./premake4_linux64 --double gmake
./premake4_osx --double --enable_pybullet gmake" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>cd gmake
make
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="cd gmake
make" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，在 Linux 上，您需要使用 cmake 来构建 pybullet，因为编译器存在混合共享库和静态库的问题。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mac OS X Xcode</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单击 build3/xcode4.command 或在终端窗口中执行</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>./premake_osx xcode4
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./premake_osx xcode4" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-usage" class="anchor" aria-hidden="true" tabindex="-1" href="#usage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用法</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">App_ExampleBrowser 可执行文件将位于 bin 文件夹中。</font><font style="vertical-align: inherit;">您可以通过终端/命令提示符或单击它来运行它。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>[--start_demo_name="Demo Name"]     Start with a selected demo  
[--mp4=moviename.mp4]               Create a mp4 movie of the window, requires ffmpeg installed
[--mouse_move_multiplier=0.400000]  Set the mouse move sensitivity
[--mouse_wheel_multiplier=0.01]     Set the mouse wheel sensitivity
[--background_color_red= 0.9]       Set the red component for background color. Same for green and blue
[--fixed_timestep= 0.0]             Use either a real-time delta time (0.0) or a fixed step size (0.016666)
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="[--start_demo_name=&quot;Demo Name&quot;]     Start with a selected demo  
[--mp4=moviename.mp4]               Create a mp4 movie of the window, requires ffmpeg installed
[--mouse_move_multiplier=0.400000]  Set the mouse move sensitivity
[--mouse_wheel_multiplier=0.01]     Set the mouse wheel sensitivity
[--background_color_red= 0.9]       Set the red component for background color. Same for green and blue
[--fixed_timestep= 0.0]             Use either a real-time delta time (0.0) or a fixed step size (0.016666)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以使用鼠标拾取来抓取对象。</font><font style="vertical-align: inherit;">按住 ALT 或 CONTROL 键时，您可以使用 Maya 风格的相机鼠标控制。</font><font style="vertical-align: inherit;">按 F1 创建一系列屏幕截图。</font><font style="vertical-align: inherit;">按 ESCAPE 退出演示应用程序。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查看文档文件夹和 Bullet 物理论坛以获取更多信息。</font></font></p>
</article></div>
