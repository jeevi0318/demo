# Neuron Pack: canvas

This pack is managed and version-controlled. Pack ID: `e8fc44f1-c739-49f5-8f71-5e97fc96f8e7`.

## Workflows (Neurons)

### Neuron: durable test

- **Type**: `interactive`
- **Topology Profile**: `None`

**Description**:


### Neuron: cyclic test

- **Type**: `interactive`
- **Topology Profile**: `None`

**Description**:


### Neuron: linear test

- **Type**: `interactive`
- **Topology Profile**: `None`

**Description**:


### Neuron: Atomic Transform

- **Type**: `interactive`
- **Topology Profile**: `atomic_io`

**Description**:


#### Topology Diagram

```mermaid
graph TD
  c1["Apply Data Transform"]
```

#### Components (Cells)

- **Apply Data Transform** (`compute_transform`)

### Neuron: atomic test

- **Type**: `interactive`
- **Topology Profile**: `None`

**Description**:


#### Topology Diagram

```mermaid
graph TD
  cell_1782043231603_0["cell_1782043231603_0"]
  cell_1782043231603_1["cell_1782043231603_1"]
  cell_1782043231603_0 --> cell_1782043231603_1
```

#### Components (Cells)

- **Unnamed Cell** (`compute_transform`)
  * **Input Schema**:
    ```json
    {
      "type": "object"
    }
    ```
  * **Output Schema**:
    ```json
    {
      "type": "object"
    }
    ```
- **Unnamed Cell** (`compute_cryptography`)
  * **Input Schema**:
    ```json
    {
      "type": "object"
    }
    ```
  * **Output Schema**:
    ```json
    {
      "type": "object"
    }
    ```
