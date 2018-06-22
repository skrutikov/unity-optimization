
- Test serialized data like audio files, Prefabs and Scriptable Objects in build mode (as they are sometimes much slower in the build then in the Editor). <sup>1</sup>
- Prefer `GetComponent<T>` over `GetComponent(typeof(T))` and over `GetComponent(string)`. <sup>1</sup>
- Avoid empty Unity-callbacks especially empty `Update()`-methods. <sup>1</sup>
- Prefer `(object)myComponent != null` or `Syste.Object.ReferenceEquals(myComponent, null)` over `myComponent == null` if `myComponent` is of type `UnityEngine.Component`. <sup>1, 2</sup>
- Prefer `myGameObject.CompareTag("MyTag")` over `myGameObject.tag == "MyTag"`. <sup>1</sup>


<sup>1</sup> [Unity 2017 Game Optimization](https://www.packtpub.com/game-development/unity-2017-game-optimization-second-edition)

<sup>2</sup> http://bonusdisc.com/null-references-in-unity/

<sup>3</sup> https://youtu.be/_wxitgdx-UI

