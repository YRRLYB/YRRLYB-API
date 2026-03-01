# 🌸 伊利布 API (YRRLYB API)

> 高质量二次元图片 API 接口，精选美少女角色图片。提供随机（全部）、竖屏（手机壁纸）和横屏（电脑壁纸）等多种模式，**总图库量 10000+**。

感谢 Skri 提供的部分技术支持。
本项目适用在个人博客、bot等项目中使用。

## ✨ API Logo

<p align="center">
  <img src="https://github.com/YRRLYB/YRRLYB-API/blob/main/%E4%BC%8A%E5%88%A9%E5%B8%83api.png" alt="伊利布 API Logo" width="700"/>
</p>

## 📌 接口调用说明

* **默认访问：** 不带 `type` 参数时，直接返回一张随机图片链接并自动重定向。
    * **示例：** `https://photo.yrrlyb.online/api.php?sort=random`

* **JSON 格式：** 添加参数 `?type=json`，将返回包含图片数组的 JSON 数据。

* **批量数量：** 在 **JSON 模式**下，可通过 `?num=N` (N 为 1-100 的数字) 参数指定返回图片的数量。
    * **示例 (JSON & 数量)：** `https://photo.yrrlyb.online/api.php?sort=random&type=json&num=5`

---

## 🚀 接口地址列表

接口的图片模式由 `sort` 参数控制。

### 1. 随机模式 (`sort=random`) - 全部尺寸

| `sort` 参数 | 线路描述 | 接口地址 |
| :--- | :--- | :--- |
| **`random`** | 国内外通用 | `https://photo.yrrlyb.online/api.php?sort=random` |
| **`randomlyb`** | 外网专用 (lyb线路) | `https://photo.yrrlyb.online/api.php?sort=randomlyb` |

### 2. 竖屏模式 (`sort=mp`) - 手机壁纸

| `sort` 参数 | 线路描述 | 接口地址 |
| :--- | :--- | :--- |
| **`mp`** | 国内外通用 | `https://photo.yrrlyb.online/api.php?sort=mp` |
| **`mplyb`** | 外网专用 (lyb线路) | `https://photo.yrrlyb.online/api.php?sort=mplyb` |

### 3. 横屏模式 (`sort=pc`) - 电脑壁纸

| `sort` 参数 | 线路描述 | 接口地址 |
| :--- | :--- | :--- |
| **`pc`** | 国内外通用 | `https://photo.yrrlyb.online/api.php?sort=pc` |
| **`pclyb`** | 外网专用 (lyb线路) | `https://photo.yrrlyb.online/api.php?sort=pclyb` |

---

## 📜 许可证 (License)

本项目代码根据 **[定制MIT 许可证](LICENSE)** 的条款进行许可。

## ⚖️ 服务条款 (Terms of Service)

* **本api为个人搭建，为爱发电。禁止用在商业用途，本api仅供学习交流，图片版权归原作者所有，不能完全保证api的可用性，api禁止爬虫** 
* **api持续性开放并继续录入全新图片** 
