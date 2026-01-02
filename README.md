# 3D Avatar Rigging and Web Control Project

## Overview

This project demonstrates how a 3D human avatar can be rigged, imported, and controlled inside a web application. The main focus of this work is to understand the complete flow from 3D model preparation to real-time interaction in the browser using quaternion-based transformations.

The 3D model used in this project was rigged using **Mixamo** and rendered on the web using **Three.js**.

---

## 3D Model Used

* The human avatar was rigged using **Mixamo**
* Mixamo was used to automatically generate the skeleton (bones) for the character
* The character was kept in a **T-pose** and downloaded in `.glb` format
* No pre-made animations were used; only the rigged model was exported

---

## Tools and Technologies

* **Mixamo** – for automatic character rigging
* **Blender** – for basic inspection and verification of the rig
* **Three.js** – for rendering and controlling the avatar in the browser
* **HTML / JavaScript** – for UI and interaction

---

## Process Followed (In Simple Words)

1. First, the 3D character was uploaded to **Mixamo**
2. Automatic rigging was applied to generate bones for the character
3. The rigged character was downloaded in `.glb` format
4. The model was loaded into a Three.js scene using `GLTFLoader`
5. The skeleton and bones were extracted from the loaded model
6. UI controls (buttons/sliders) were created to control body parts
7. Bone movements were applied using **quaternions only**
8. The avatar pose can be reset back to the default state

---

## Web Application Features

* Renders a 3D human avatar in the browser
* Allows camera rotation using orbit controls
* Provides controls to move arms and legs
* All bone movements are handled using quaternion-based rotations
* Reset option to bring the avatar back to its original pose

---



## Conclusion

This project helped me understand the complete pipeline of working with 3D characters, starting from rigging in Mixamo to controlling the avatar in a web application. It gave me hands-on experience with Three.js, skeleton manipulation, and quaternion-based transformations, which are important concepts in real-time 3D applications.


