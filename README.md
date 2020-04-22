# libdrm-2.4.101_gnome_hide_panel_3.36.1_hide_bar_panel
libdrm-2.4.101 , amd64 , wayland , plank conflict hide , omap , libkms , freedreno , exynos , xf86drm , include


1) install mesa-20.0.2_V3

install https://github.com/Griggorii/mesa-20.0.2_V3

2) open in folder libdrm-2.4.101_gnome_hide_panel_3.36.1 terminal run command copy paste enter

$ sudo tar xvpf libdrm-2.4.101_gnome_hide_panel.tar.xz  -C /

3) power internet reinstall stable nouveau NVD7 terminal run command copy paste enter

$ sudo apt update && sudo apt --reinstall install libdrm-amdgpu1 libdrm-intel1 libdrm-nouveau2 libdrm-radeon1 libdrm2 -y && sudo rm -rf /etc/modprobe.d/blacklist-nvidia-nouveau.conf

Proview https://youtu.be/Co-6k1I_TmQ
