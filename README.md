<img width="1070" height="590" alt="image" src="https://github.com/user-attachments/assets/6471ccac-ad3b-48d9-9a9d-118681097229" /># 🎨 Style Transfer with VGG19

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
    <td><strong><img width="1070" height="590" alt="image" src="https://github.com/user-attachments/assets/449d2bb6-ccf4-484a-87ae-bf15bfce000d" />
</strong></td>
    <td><strong><img width="1070" height="590" alt="image" src="https://github.com/user-attachments/assets/333f5b96-0871-4e15-8e67-e07b5deec82f" />
</strong></td>
    <td><strong><img width="425" height="435" alt="image" src="https://github.com/user-attachments/assets/aefd480e-98bd-4b79-9d2f-9ba403ac73cf" />
</strong></td>
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
