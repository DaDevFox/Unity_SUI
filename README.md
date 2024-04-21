# Unity SUI (Styled UI)
Library which allows multi-object affecting changes to basic visual properties such as color, font style and size, margin, and padding in Unity image-rendered UI components (traditional components; not UIElements).

# Components
components such as `SPanel` (Styled Panel), `SButton`, `SText` (requires TextMeshPro -- integrated into Unity since Unity 202X) must be added to UI GameObjects (if required builtin components such as `Image`s or `Button`s are missing, they will be added automatically. 

These components reference a (`ScriptableObject`/`Asset`) `Theme` object which holds 'templates' to apply -- collections of values for fonts, colors, etc.
