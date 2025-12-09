# Practical-Final-Exam
My practical final exam

Errors:
Shaders not showing in the game build due to not having change in the code "RenderPipeline" = "UniversalRenderPipeline" supposed to be UniversalPipeline

<img width="499" height="576" alt="{B97135EA-8C34-4C45-B2B8-2666FC3DFDC8}" src="https://github.com/user-attachments/assets/1a14e839-fe77-4a8c-b8a1-92b5408cc830" />




How I made Rim Lighting + Hologram Shader:
<img width="600" height="45" alt="{3E126A34-BAC8-4338-8BE4-F6DCAFC5197D}" src="https://github.com/user-attachments/assets/bff59403-8071-429a-b6e3-f7035e96e6e5" />
<img width="921" height="114" alt="{C9CBC9F9-D951-441F-9134-B545C13544DA}" src="https://github.com/user-attachments/assets/6218fab9-7d11-41b1-9656-e01d1c25b703" />
<img width="763" height="71" alt="{D5426929-5A67-4F2E-99B3-47DF7887294A}" src="https://github.com/user-attachments/assets/26a83021-7b84-473d-a17e-bccdf685eea0" />


I created the rim lighting by first setting up the rimcolor variable that stores the color of the rim lighting and the rim power aka the strtength of the rim lighting. I then in the fragment shader applied the rim lighting effect then proceeding to do the math for the rim lighting effect. I then applied it to the final color and behold rim lighting with hologram. I decided to do this instead of a typical fresenel effect as the rim lighting looked alot better with basicn rim lighting instead of fresnel.


