---
ID_PAGE: 25307
PG_TITLE: MeshAssetTask
PG_VERSION: 2.1
TAGS:
    - Mesh
    - Assets
---
## Description

class [MeshAssetTask](/classes/3.0/MeshAssetTask)

Load the task on the given [Mesh](/classes/3.0/Mesh)

## Constructor

## new [MeshAssetTask](/classes/3.0/MeshAssetTask)(name, meshesNames, rootUrl, sceneFilename)

The [MeshAssetTask](/classes/3.0/MeshAssetTask) constructor

#### Parameters
 | Name | Type | Description
---|---|---|---
 | name | string |      The name
 | meshesNames | any |      The meshes names
 | rootUrl | string |      The root url for this mesh
## Members

### name : string

The task name

### meshesNames : any

The meshes names to load

### rootUrl : string

The root url for this mesh

### sceneFilename : string

The babylon file name

### loadedMeshes : Array&lt;[AbstractMesh](/classes/3.0/AbstractMesh)&gt;

The loaded meshes

### loadedParticleSystems : Array&lt;[ParticleSystem](/classes/3.0/ParticleSystem)&gt;

The loaded Particule system linked to this mesh

### loadedSkeletons : Array&lt;[Skeleton](/classes/3.0/Skeleton)&gt;

The loaded Skeletons linked to this mesh

### onSuccess : (task: IAssetTask) =&gt; void

Function call when the mesh is load successfully

### onError : (task: IAssetTask) =&gt; void

Function call when the mesh isn't load successfully

### isCompleted : boolean

True if is completed, false otherwise.

## Methods

### run(scene, onSuccess, onError) &rarr; void



#### Parameters
 | Name | Type | Description
---|---|---|---
 | scene | [Scene](/classes/3.0/Scene) |      The scene where mesh is.
 | onSuccess | () =&gt; void |      Function call when the mesh is load successfully
 | onError | () =&gt; void |      Function call when the mesh isn't load successfully
