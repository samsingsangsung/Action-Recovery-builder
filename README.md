# Build recovery with Github action
```
Supports TWRP building.
```
---
## Params:
| Name            | Description         | Example |
|-----------------|--------------|---------|
| `LIBRARY_NAME`  | Source type  | omni    |
| `LIBRARY_URL`   | Source address | https://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git |
| `LIBRARY_BRANCH`| Source branch| twrp-9.0 |
| `DEVICE_URL`    | Device address  | https://github.com/azwhikaru/twrp_device_xiaomi_archytas |
| `DEVICE_BRANCH` | Device branch| twrp-9.0 |
| `DEVICE_PATH`   | Device path  | device/xiaomi/Archytas |
| `DEVICE_NAME`   | Device name  | Archytas |

---

## How to Use
#### 1. Fork the project
![](https://i.bmp.ovh/imgs/2021/10/6b6ed9f29e732372.png)
#### 2. Go to your forked project
![](https://i.bmp.ovh/imgs/2021/10/66cfe324c0ebb69b.png)
#### 3. Click "Actions", then "Make Recovery"
![](https://i.bmp.ovh/imgs/2021/10/23896d1b66292047.png)
#### 4. Click "Run workflow" and fill the params as needed
![](https://i.bmp.ovh/imgs/2021/10/9cb7871267cf2f53.png)
#### 5. Press the "Run workflow" to start building.
---
## Builds
#### [Release](../../releases)
---
## Acknowledgements:
#### https://github.com/samsingsangsung/Action-Recovery-builder for the builder. Thank you!
