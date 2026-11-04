# Skill 剪辑台 · 插件市场

[Skill 剪辑台](https://claude.ai/artifact/CfNyZ33MiZLQaXryzgZYZ1) 的 Claude Code 插件市场：按制作流程整理的 AI 视频 skill 中，已打包成插件的那些。

```
/plugin marketplace add ndze5588-afk/video-skill-hub-plugins
/plugin install remotion@video-skill-hub
/plugin install hyperframes@video-skill-hub
/plugin install heygen@video-skill-hub
/plugin install higgsfield@video-skill-hub
/plugin install ffmpeg-skill@video-skill-hub
```

| 插件 | 来源 | 说明 |
| --- | --- | --- |
| `remotion` | [remotion-dev/claude-code-plugin](https://github.com/remotion-dev/claude-code-plugin) | Remotion 官方出品，教 agent 用 React 写视频：时间轴、动画、音频、字幕、渲染都有专门的 skill，减少时序和素材引用上的常见错误。 |
| `hyperframes` | [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | HeyGen 开源的「写 HTML 出视频」框架，附带一组 skill：合成画面、GSAP 动画、字幕、配音、网页转视频，以及把 Remotion 项目迁移过来。 |
| `heygen` | [heygen-com/skills](https://github.com/heygen-com/skills) | 用一张照片建数字分身，生成真人出镜的口播视频；也能把已有视频翻译成 175+ 种语言，保留原声并对口型。 |
| `higgsfield` | [higgsfield-ai/skills](https://github.com/higgsfield-ai/skills) | 调用 Higgsfield 生成图片、视频、3D 和音频，另有现成的场景 skill：无露脸短视频、讲解视频、YouTube 封面、产品图、品牌套件。 |
| `ffmpeg-skill` | [kajisho5/ffmpeg-skill](https://github.com/kajisho5/ffmpeg-skill) | 本地 FFmpeg 剪辑工具箱，42 个工具：剪切、字幕、画幅重构、响度标准化、按平台导出。先探测再动手、做完再校验，不上云、不要 key。 |

全部 29 个视频 skill（含未打包成插件的）、依赖和 API key 说明见 https://claude.ai/artifact/CfNyZ33MiZLQaXryzgZYZ1 。

本仓库由 Skill 剪辑台自动生成。插件归各自作者所有，适用其仓库中的许可证；本仓库中的整理内容采用 [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/deed.zh-hans)，转载请注明出处。
