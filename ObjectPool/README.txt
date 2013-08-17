   [Unity3D Object Pool]

   Intended for open modification and redistribution via GitHub accessible
   at https://github.com/burningship/unity3d-objectpool.
   
   A class type intended to ease the management of large-scale spawning and
   destruction of any gameobjects (in scene or as a prefab) at runtime.
   
   
   
   [Usage]

   Import the Assets.ObjectPool namespace into any script in your project
   and declare the ObjectPool class as you would with any container class.
   
   The ObjectPool accepts a gameobject instance as a parameter, enabling you
   to spawn and destroy objects of this type. Only one gameobject type per 
   ObjectPool declared, so if you intend to spawn myriad gameobject types,
   declare more ObjectPools to manage them.
   
   Then you can call Create() and Destroy() methods on an ObjectPool instance.
   
   If you wish to set an object to self-destruct a set amount of time after
   being created, construct the ObjectPool with a MonoBehaviour argument
   (typically 'this') and assign the time in seconds on Create(vector3, float);



   Copyright 2013 [Liam David Jenkin]

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

   Licensed under [Apache License, Version 2.0]
