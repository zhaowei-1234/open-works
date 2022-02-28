## 如视公开 Work 数据集。

**Work** 是通过如视硬件设备（[如视扫描仪](https://realsee.com/website/product/hardware) 、[如视 Lite 全景相机](https://realsee.com/website/product/lite) 、[如视 VR App](https://realsee.com/website/mobile) ）扫描并算法加工之后生成的用于描述三维空间展示的数据。

为便于开发、调试和研究，我们面向开源社区公开部分 **Work** 数据集。

## Usage

### 获取 Work 数据 

```ts
// JSON
import workJson from "@realsee/open-works/virtual/81RojBlJQdVTglNNMr/work.json"

// ES Modules
import { work } from "https://cdn.skypack.dev/@realsee/open-works/virtual/81RojBlJQdVTglNNMr/work";

```

### 获取户型图、房间标签等附加数据

```ts
// JSON
import workJson from "@realsee/open-works/virtual/81gmMq5a7zbF9leWMk/work.json"  // work
import floorplanServerDataJson from "@realsee/open-works/virtual/81gmMq5a7zbF9leWMk/floorplanServerData.json"  // floorplanServerData
import modelRoomLabelsJson from "@realsee/open-works/virtual/81gmMq5a7zbF9leWMk/modelRoomLabels.json"  // modelRoomLabels


// ES Modules
import { 
    work,
    floorplanServerData,
    modelRoomLabels
} from "https://cdn.skypack.dev/@realsee/open-works/virtual/81gmMq5a7zbF9leWMk/index";
```

