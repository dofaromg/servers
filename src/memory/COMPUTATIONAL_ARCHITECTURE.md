# Computational Architecture Knowledge Base
# CPU/GPU 處理器架構知識庫

This knowledge graph defines the fundamental concepts of CPU and GPU architectures, their characteristics, and relationships for use as an AI supercomputer database.

## Entities (實體定義)

### Processors (處理器)

| Entity | Type | Description |
|--------|------|-------------|
| CPU | Processor | Central Processing Unit - Few powerful cores optimized for complex logic |
| GPU | Processor | Graphics Processing Unit - Thousands of simple cores for parallel tasks |

### Processing Units (處理單元)

| Entity | Type | Description |
|--------|------|-------------|
| CPUCore | ProcessingUnit | Powerful, versatile cores for diverse instructions |
| GPUCore | ProcessingUnit | Simplified cores optimized for mathematical operations |

### Computing Modes (運算模式)

| Entity | Type | Description |
|--------|------|-------------|
| SerialProcessing | ComputingMode | 序列化處理 - One task at a time, sequential execution |
| ParallelProcessing | ComputingMode | 平行處理 - Many tasks simultaneously |

### Application Domains (應用領域)

**CPU-Optimized:**
- SystemOperations - OS management, resource allocation
- WebBrowsing - JavaScript, DOM manipulation  
- DocumentProcessing - 文書處理 - Word processing, spreadsheets

**GPU-Optimized:**
- GraphicsRendering - 圖形渲染 - 3D scenes, shaders
- Gaming - 遊戲 - Real-time graphics and physics
- VideoEditing - 影片編輯 - Frame processing
- DeepLearning - 深度學習 - Neural networks, model training
- ScientificComputing - 科學計算 - Simulations, modeling
- BigData - 大數據 - Large-scale data analytics

### System Architecture (系統架構)

| Entity | Type | Description |
|--------|------|-------------|
| ModernComputingSystem | SystemArchitecture | Heterogeneous CPU+GPU architecture |
| AIAcceleration | TechnologyCapability | AI/ML computation acceleration |

## Relations (關係定義)

### Core Relationships

```
CPU --uses--> SerialProcessing
CPU --contains--> CPUCore
GPU --uses--> ParallelProcessing  
GPU --contains--> GPUCore
```

### Application Optimization

```
CPU --optimizedFor--> SystemOperations, WebBrowsing, DocumentProcessing
GPU --optimizedFor--> GraphicsRendering, Gaming, VideoEditing, DeepLearning, ScientificComputing, BigData
```

### System Integration

```
ModernComputingSystem --contains--> CPU, GPU
CPU --coordinatesIn--> ModernComputingSystem
GPU --acceleratesIn--> ModernComputingSystem
CPU --complementsWith--> GPU
GPU --complementsWith--> CPU
```

## Core Differences Summary (核心差異總結)

| Aspect | CPU | GPU |
|--------|-----|-----|
| 運算模式 | 序列化處理 (Serial) | 平行處理 (Parallel) |
| 核心數量 | Few but powerful | Many but simplified |
| 核心能力 | Versatile/General | Specialized/Focused |
| 主要應用 | System tasks, complex logic | Graphics, AI, big data |
| 比喻 | 博士生 (PhD Student) | 數學系學生 (Math Students) |

## Usage

This knowledge graph can be loaded into the MCP Memory Server:

```bash
# Set the memory file path to use this knowledge base
export MEMORY_FILE_PATH=/path/to/computational_architecture.jsonl

# Or copy to the default memory location
cp computational_architecture.jsonl memory.jsonl
```

Then use the memory server tools to query:
- `search_nodes` - Search by keyword (e.g., "parallel", "GPU", "深度學習")
- `open_nodes` - Open specific entities by name
- `read_graph` - Read the entire knowledge graph
- `create_entities` - Add new entities
- `create_relations` - Add new relationships

## Extending the Knowledge Base

Add new entities following the JSONL format:
```json
{"type":"entity","name":"NewConcept","entityType":"Category","observations":["Description 1","Description 2"]}
{"type":"relation","from":"EntityA","to":"EntityB","relationType":"relationName"}
```
