# Ex-1-Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine

# AIM:
The aim is to Implement various effects in a material such as emissive, roughness and metallic properties in Unreal Engine.

# Procedure:

**Create a New Material:**

- Open your Unreal Engine 5 project.

- In the Content Browser, Right-click → Material.

- Name it something like M_TestMaterial.

- Double-click to open the Material Editor.

**Basic Setup (Base Color):**

* Add a Vector Parameter:

- Right-click in the graph → search Vector Parameter → name it BaseColor.

- Set it to any color you want.

* Connect it to the Base Color input of the Material Output node.

**Emissive Color:**

* Add a Multiply node:

* Right-click → search Multiply.

* Add a Vector Parameter:

* Name it EmissiveColor → pick a bright color like blue or green.

* Add a Scalar Parameter:

* Name it EmissiveIntensity → set default value like 10.0.

* Connect EmissiveColor to A of Multiply. EmissiveIntensity to B of Multiply.

* Multiply output → Emissive Color input of Material Output.

**Roughness:**

* Add a Scalar Parameter:

* Name it Roughness → set default value between 0.0 (shiny) and 1.0 (matte).

* Connect it to the Roughness input of Material Output.

**Metallic:**

* Add another Scalar Parameter:

* Name it Metallic → default 0.0 for non-metal, 1.0 for metal.

* Connect it to the Metallic input of Material Output.

# Output:

<br>

**Base color:**

<br>

![image](https://github.com/user-attachments/assets/23f70e04-9775-4fcc-bfb7-59b877ff9073)
![image](https://github.com/user-attachments/assets/2a4b6239-cbe6-4554-8e6c-ccf854bf53a1)

<br>

**Emissive Color:**

<br>

![image](https://github.com/user-attachments/assets/b6ce28d9-581a-4485-90c1-7c8f4d3c84e5)
![image](https://github.com/user-attachments/assets/74602ebd-7599-47e6-96ea-a721e823c4de)

<br>

**Roughness:**

<br>

![image](https://github.com/user-attachments/assets/51b61a6b-2b52-422d-a0f6-79ec768eaed0)
![image](https://github.com/user-attachments/assets/39fbccd7-ad78-4297-ba0b-c16a8045dd85)

<br>

**Metallic:**

<br>

![image](https://github.com/user-attachments/assets/fc83b716-925a-4808-bc9d-4ba716250179)
![image](https://github.com/user-attachments/assets/eff0cf83-c6ed-4955-826a-05477134e9bc)

<br>

# Reault:
Thus various effects in material properties is sucessfully implemented in unreal engine.
