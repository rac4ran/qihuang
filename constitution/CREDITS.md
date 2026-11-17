# 图片素材说明

`public/constitution/` 下的九张舌象图，是本站在公开的中医舌诊科普资料中检索挑选的教学用照片，
经统一裁切（4:3）、轻微调色与 WebP 压缩后使用，文件名为 `tongue-<体质>.webp`。

| 文件 | 体质 | 图中要点 |
| --- | --- | --- |
| `tongue-pinghe-v2.webp` | 平和质 | 舌质淡红、苔薄白而匀 |
| `tongue-qixu-v2.webp` | 气虚质 | 舌体偏胖、舌边齿痕 |
| `tongue-yangxu-v2.webp` | 阳虚质 | 舌淡胖、苔白润 |
| `tongue-yinxu-v2.webp` | 阴虚质 | 舌红少苔、舌面裂纹 |
| `tongue-tanshi-v3.webp` | 痰湿质 | 舌体胖大、苔白厚腻 |
| `tongue-shire-v2.webp` | 湿热质 | 舌质偏红、苔黄厚腻 |
| `tongue-xueyu-v2.webp` | 血瘀质 | 舌质紫暗、舌面瘀点 |
| `tongue-qiyu-v5.webp` | 气郁质 | 舌形偏尖、舌质接近正常 |
| `tongue-tebing-v6.webp` | 特禀质 | 舌象接近正常（复用平和质的正常舌照片，取景更近） |

## 关于授权

这些图片来自互联网上公开发布的中医科普内容，仅用于本站的教学演示，本站不对其主张版权。
若你要把站点用于公开或商业环境，建议：

1. 换成本单位拍摄或已获授权的临床舌象图；
2. 或使用开放许可的医学影像库（如 Openverse、Wikimedia Commons 中的 CC0/CC BY 素材）并在页面标注署名与许可；
3. 直接替换 `public/constitution/` 下的同名文件即可，无需改代码；若文件名变化，同步更新
   `src/features/constitution/photos.ts` 里的 `src` 字段。

## 面色为什么是示意图

面色/肤色涉及真人肖像与隐私，公开渠道难以获得授权明确的临床照片，因此这一栏使用
`src/components/constitution/FaceDiagram.tsx` 绘制的示意图，只讲「该留意哪一处」，
并在页面上明确标注为「示意」。
