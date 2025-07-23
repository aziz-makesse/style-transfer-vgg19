# Style Transfer with VGG19

This project implements **Neural Style Transfer** using PyTorch and a pre-trained **VGG19** model.  
It blends the **content** of one image (Cristiano Ronaldo) with the **style** of another (a painting by Van Gogh), producing a visually artistic output.

---

## What is Neural Style Transfer?

Neural Style Transfer is a technique that combines the **content** of one image with the **style** of another using deep learning.  
This implementation is based on the paper *"A Neural Algorithm of Artistic Style"* by Gatys et al.

---

## Example

<table>
  <tr>
    <td><strong>Style Image (Van Gogh) | Content Image (Cristiano Ronaldo)</strong></td>
    <td><strong>Output Image</strong></td>
  </tr>
  <tr>
    <td><img width="1070" height="590" alt="image" src="https://github.com/user-attachments/assets/86e064fe-815d-4716-85f9-628c10d73fa3" />
</td>
    <td><img width="425" height="435" alt="image" src="https://github.com/user-attachments/assets/2130d8f2-f620-4cc2-8243-4e4530bf3b19" />
</td>
  </tr>
</table>

---

## Requirements

Make sure you have Python ≥ 3.8 and the following libraries installed:

```bash
pip install torch torchvision matplotlib pillow
