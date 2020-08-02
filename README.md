# DnCNN

An implementation of a CNN denoiser!

References: [Beyond a Gaussian Denoiser: Residual Learning of
Deep CNN for Image Denoising][1].

This network has been trained for noise with <b>standard deviation in the range of 5 to 40.</b>

Results:

<figure>
  <img src="./results/tiger_noisy.png" alt="noisy_tiger" width = 300px>
  <figcaption>Noisy image of a Tiger</figcaption>
</figure>

<br><br>

<figure>
  <img src="./results/tiger_denoised.png" alt="denoised_tiger" width = 300px>
  <figcaption>Denoised image of the Tiger</figcaption>
</figure>

<br><br>

<figure>
  <img src="./results/plane_noisy.png" alt="noisy_tiger" width = 300px>
  <figcaption>Noisy image of a plane</figcaption>
</figure>

<br><br>

<figure>
  <img src="./results/plane_denoised.png" alt="denoised_tiger" width = 300px>
  <figcaption>Denoised image of the plane</figcaption>
</figure>

<br><br>

 <table style="width:100%">
  <tr>
    <th>Image</th>
    <th>Standard Deviation of Noise</th>
    <th>Input PSNR(dB)</th>
    <th>Input SSIM</th>
    <th>Output PSNR(dB)</th>
    <th>Output SSIM</th>
  </tr>
  <tr>
    <td>Tiger</td>
    <td>25</td>
    <td>16.53</td>
    <td>0.5914</td>
    <td>29.16</td>
    <td>0.9233</td>
  </tr>
  <tr>
    <td>Plane</td>
    <td>35</td>
    <td>12.83</td>
    <td>0.4875</td>
    <td>21.73</td>
    <td>0.9105</td>
  </tr>
</table> 

# Running Code
Run cells of:
```
   ./code/DnCNN_sigmix.ipynb on jupyter notebook
```

  [1]: <https://ieeexplore.ieee.org/document/7839189>
