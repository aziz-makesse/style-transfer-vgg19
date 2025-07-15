# 🎨 Style Transfer with VGG19

This project implements **Neural Style Transfer** using PyTorch and a pre-trained **VGG19** model.  
It blends the **content** of one image (Cristiano Ronaldo) with the **style** of another (a painting by Van Gogh), producing a visually artistic output.

---

## 🧠 What is Neural Style Transfer?

Neural Style Transfer is a technique that combines the **content** of one image with the **style** of another using deep learning.  
This implementation is based on the paper *"A Neural Algorithm of Artistic Style"* by Gatys et al.

---

## 🖼️ Example

<table>
  <tr>
    <td><strong>Style Image (Van Gogh)</strong></td>
    <td><strong>Content Image (Cristiano Ronaldo)</strong></td>
    <td><strong>Output Image</strong></td>
  </tr>
  <tr>
    <td><img src="images/Van_Gogh.png" width="200"/></td>
    <td><img src="images/Cristiano_Ronaldo_is_saudi.png" width="200"/></td>
    <td><img src="images/output.png" width="200"/></td>
  </tr>
</table>

---

## 📦 Requirements

Make sure you have Python ≥ 3.8 and the following libraries installed:

```bash
pip install torch torchvision matplotlib pillow
