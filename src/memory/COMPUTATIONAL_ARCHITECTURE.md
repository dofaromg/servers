# Computational Architecture Knowledge Base
# CPU/GPU 處理器架構知識庫 - 創世公式實現

This knowledge graph defines the fundamental concepts of CPU and GPU architectures, their characteristics, and relationships for use as an AI supercomputer database. **Now enhanced with the Creation Formula (創世公式) for performance amplification mapping.**

## 創世公式 (Creation Formula)

The core principle that maps **Definition × Precision → Performance Amplification**:

```
Performance = f(Definition, Precision) × AmplificationFactor

Where:
- Definition (定義): Fundamental specification of computational units
- Precision (精度): Accuracy level determining bit-width (FP64/FP32/FP16/INT8)
- AmplificationFactor: Scaling multiplier based on particle composition
```

### Amplification Mapping (放大映射)

| Precision Level | Bit Width | Throughput Multiplier | Best For |
|-----------------|-----------|----------------------|----------|
| FP64 | 64-bit | 1× (baseline) | 科學計算 Scientific Computing |
| FP32 | 32-bit | 2× | 遊戲/圖形 Gaming/Graphics |
| FP16 | 16-bit | 4× | 深度學習 Deep Learning |
| INT8 | 8-bit | 8× | AI推理 AI Inference |

### Particle Hierarchy (粒子階層)

```
ParticleDefinition (粒子定義)
    ↓ composesFrom
ParticleComposition (粒子組合)
    ↓ amplifies
Performance (效能)
```

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

### Foundation Principles (基礎原則) - NEW

| Entity | Type | Description |
|--------|------|-------------|
| Definition | FoundationPrinciple | 定義 - Specification of computational units |
| Precision | FoundationPrinciple | 精度 - Accuracy level (bit-width) |
| Performance | FoundationPrinciple | 效能 - Computational throughput |
| CreationFormula | AmplificationPrinciple | 創世公式 - The mapping principle |

### Precision Levels (精度層級) - NEW

| Entity | Type | Throughput |
|--------|------|------------|
| FP64Precision | PrecisionLevel | 1× baseline |
| FP32Precision | PrecisionLevel | 2× amplified |
| FP16Precision | PrecisionLevel | 4× amplified |
| INT8Precision | PrecisionLevel | 8× amplified |

### Creation Elements (創世元素) - NEW

| Entity | Type | Description |
|--------|------|-------------|
| ParticleDefinition | CreationElement | 粒子定義 - Fundamental unit spec |
| ParticleComposition | CreationElement | 粒子組合 - Assembly of particles |
| AmplificationMapping | CreationElement | 放大映射 - Transform function |

### Performance Resources (效能資源) - NEW

| Entity | Type | Description |
|--------|------|-------------|
| ThroughputAmplification | AmplificationMetric | 吞吐量放大 |
| LatencyReduction | AmplificationMetric | 延遲降低 |
| MemoryBandwidth | PerformanceResource | 記憶體頻寬 |
| ComputeDensity | PerformanceResource | 運算密度 |

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

### Creation Formula Relations (創世公式關係) - NEW

```
Definition --determines--> Performance
Precision --affects--> Performance
CreationFormula --utilizes--> Definition, Precision
CreationFormula --amplifies--> Performance
```

### Precision to Application Mapping (精度應用映射) - NEW

```
FP64Precision --requiredFor--> ScientificComputing
FP32Precision --usedIn--> Gaming, GraphicsRendering
FP16Precision --optimizedFor--> DeepLearning
INT8Precision --enables--> AIAcceleration
```

### Amplification Relations (放大關係) - NEW

```
GPU --excelsAt--> ThroughputAmplification
CPU --excelsAt--> LatencyReduction
FP16Precision --doubles--> ThroughputAmplification
INT8Precision --quadruples--> ThroughputAmplification
MemoryBandwidth --enables--> ThroughputAmplification
```

### Particle Hierarchy (粒子階層) - NEW

```
CPUCore --definedBy--> ParticleDefinition
GPUCore --definedBy--> ParticleDefinition
ParticleComposition --composesFrom--> ParticleDefinition
AmplificationMapping --implements--> CreationFormula
ParticleComposition --amplifies--> Performance
```

## Core Differences Summary (核心差異總結)

| Aspect | CPU | GPU |
|--------|-----|-----|
| 運算模式 | 序列化處理 (Serial) | 平行處理 (Parallel) |
| 核心數量 | Few but powerful | Many but simplified |
| 核心能力 | Versatile/General | Specialized/Focused |
| 主要應用 | System tasks, complex logic | Graphics, AI, big data |
| 比喻 | 博士生 (PhD Student) | 數學系學生 (Math Students) |
| 放大優勢 | LatencyReduction | ThroughputAmplification |
| 最佳精度 | FP64/FP32 | FP16/INT8 |

## 創世公式效能放大表 (Performance Amplification Table) - NEW

| Configuration | Definition | Precision | Amplification |
|---------------|------------|-----------|---------------|
| CPU + FP64 | Complex | Maximum | 1× (baseline) |
| CPU + FP32 | Complex | Standard | 2× throughput |
| GPU + FP32 | Simple×1000s | Standard | 100-1000× parallel |
| GPU + FP16 | Simple×1000s | Half | 200-2000× parallel |
| GPU + INT8 | Simple×1000s | Quantized | 400-4000× parallel |

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
