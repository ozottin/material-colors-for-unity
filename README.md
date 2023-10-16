# material-colors-for-unity
A list of material color constants that you can add to your unity project to quickly reference any color you want!

## How to use

Save the MaterialColors.cs to you project and reference colors like below:

```
using UnityEngine;

public class Example : MonoBehaviour
{
    public Material myMaterial;

    void Start()
    {
        // Set the material color to a pastel red
        myMaterial.color = MaterialColors.Red500;
    }
}
```
