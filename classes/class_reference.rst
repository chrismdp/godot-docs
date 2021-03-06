.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the Reference.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_Reference:

Reference
=========

**Inherits:** :ref:`Object<class_Object>`

**Inherited By:** :ref:`RegExMatch<class_RegExMatch>`, :ref:`RegEx<class_RegEx>`, :ref:`EncodedObjectAsID<class_EncodedObjectAsID>`, :ref:`SpatialGizmo<class_SpatialGizmo>`, :ref:`TriangleMesh<class_TriangleMesh>`, :ref:`AnimationTrackEditPlugin<class_AnimationTrackEditPlugin>`, :ref:`EditorScenePostImport<class_EditorScenePostImport>`, :ref:`Expression<class_Expression>`, :ref:`PhysicsShapeQueryResult<class_PhysicsShapeQueryResult>`, :ref:`EditorSceneImporter<class_EditorSceneImporter>`, :ref:`Physics2DTestMotionResult<class_Physics2DTestMotionResult>`, :ref:`FuncRef<class_FuncRef>`, :ref:`File<class_File>`, :ref:`TCP_Server<class_TCP_Server>`, :ref:`Physics2DShapeQueryResult<class_Physics2DShapeQueryResult>`, :ref:`ConfigFile<class_ConfigFile>`, :ref:`StreamPeer<class_StreamPeer>`, :ref:`GDScriptNativeClass<class_GDScriptNativeClass>`, :ref:`HTTPClient<class_HTTPClient>`, :ref:`AudioStreamPlayback<class_AudioStreamPlayback>`, :ref:`VisualScriptFunctionState<class_VisualScriptFunctionState>`, :ref:`EditorInspectorPlugin<class_EditorInspectorPlugin>`, :ref:`Resource<class_Resource>`, :ref:`KinematicCollision<class_KinematicCollision>`, :ref:`SurfaceTool<class_SurfaceTool>`, :ref:`JSONParseResult<class_JSONParseResult>`, :ref:`SpatialVelocityTracker<class_SpatialVelocityTracker>`, :ref:`EditorResourcePreviewGenerator<class_EditorResourcePreviewGenerator>`, :ref:`Physics2DShapeQueryParameters<class_Physics2DShapeQueryParameters>`, :ref:`EditorExportPlugin<class_EditorExportPlugin>`, :ref:`ARVRInterface<class_ARVRInterface>`, :ref:`UPNP<class_UPNP>`, :ref:`EditorScript<class_EditorScript>`, :ref:`MultiplayerAPI<class_MultiplayerAPI>`, :ref:`Mutex<class_Mutex>`, :ref:`PacketPeer<class_PacketPeer>`, :ref:`Semaphore<class_Semaphore>`, :ref:`XMLParser<class_XMLParser>`, :ref:`EditorImportPlugin<class_EditorImportPlugin>`, :ref:`Directory<class_Directory>`, :ref:`WeakRef<class_WeakRef>`, :ref:`GDScriptFunctionState<class_GDScriptFunctionState>`, :ref:`Marshalls<class_Marshalls>`, :ref:`SceneState<class_SceneState>`, :ref:`PCKPacker<class_PCKPacker>`, :ref:`MeshDataTool<class_MeshDataTool>`, :ref:`AStar<class_AStar>`, :ref:`ResourceImporter<class_ResourceImporter>`, :ref:`EditorResourceConversionPlugin<class_EditorResourceConversionPlugin>`, :ref:`SceneTreeTimer<class_SceneTreeTimer>`, :ref:`UPNPDevice<class_UPNPDevice>`, :ref:`Thread<class_Thread>`, :ref:`ResourceInteractiveLoader<class_ResourceInteractiveLoader>`, :ref:`PackedDataContainerRef<class_PackedDataContainerRef>`, :ref:`KinematicCollision2D<class_KinematicCollision2D>`, :ref:`GDNative<class_GDNative>`, :ref:`PhysicsShapeQueryParameters<class_PhysicsShapeQueryParameters>`

**Category:** Core

Brief Description
-----------------

Base class for anything that keeps a reference count.

Methods
-------

+--------------------------+-------------------------------------------------------------+
| :ref:`bool<class_bool>`  | :ref:`init_ref<class_Reference_init_ref>` **(** **)**       |
+--------------------------+-------------------------------------------------------------+
| :ref:`bool<class_bool>`  | :ref:`reference<class_Reference_reference>` **(** **)**     |
+--------------------------+-------------------------------------------------------------+
| :ref:`bool<class_bool>`  | :ref:`unreference<class_Reference_unreference>` **(** **)** |
+--------------------------+-------------------------------------------------------------+

Description
-----------

Base class for anything that keeps a reference count. Resource and many other helper objects inherit this. References keep an internal reference counter so they are only released when no longer in use.

Method Descriptions
-------------------

  .. _class_Reference_init_ref:

- :ref:`bool<class_bool>` **init_ref** **(** **)**

  .. _class_Reference_reference:

- :ref:`bool<class_bool>` **reference** **(** **)**

Increase the internal reference counter. Use this only if you really know what you are doing.

  .. _class_Reference_unreference:

- :ref:`bool<class_bool>` **unreference** **(** **)**

Decrease the internal reference counter. Use this only if you really know what you are doing.

