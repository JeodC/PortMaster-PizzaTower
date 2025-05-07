## Pizza Tower -- PortMaster Edition
Pizza Tower is a fast paced 2D platformer, with an emphasis on movement, exploration and score attack. Featuring highly stylized pixel art inspired by the cartoons from the '90s, and a highly energetic soundtrack. This port uses texture externalization and compression to gain performance so even small linux-arm64 SoCs can run it.
It is the culmination of the combined efforts of those listed in the Thanks section below.

<div align="center">
  <table>
    <tr>
      <td align="center">
        <p align="center">Pizza Tower Launch Trailer</p>  
        <a href="https://www.youtube.com/watch?v=Wlq6fFOqI28">
          <img src="https://img.youtube.com/vi/Wlq6fFOqI28/0.jpg" alt="Pizza Tower Launch Trailer" width="300"/>
        </a>
      </td>
      <td align="center">
        <p>&nbsp;</p> <!-- Adjust spaces to match -->
        <img src="https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/2231450/ss_3e70c43ffd6f492f6e4dce7965499d41fad47052.1920x1080.jpg" alt="Pizza Tower Screenshot" width="300"/>
      </td>
    </tr>
  </table>
</div>

## Runtime Requirements
This port requires the dotnet runtime.

- Download the `dotnet-runtime-8.0.12.aarch64.squashfs` file from the runtimes folder.
- Add it to `PortMaster/libs` where the other runtimes are located.
- Rename it to `dotnet-runtime-8.0.12.squashfs`.

## Installation
- Purchase the game on Steam.
- Copy all the game data to `pizzatower/assets`.
- Have fun.

## Thanks
Tour De Pizza -- The amazing game.  
JohnnyOnFlame -- GMLoader-Next, FMOD compatibility, Game Port and [UTMT-CLI fork](https://github.com/JohnnyonFlame/UTMT-PortMaster).  
Regular Character -- Initial FMOD Research and Game Port.  
Cyril "kotzebuedog" Deletre -- Port engineering assistance (FMOD Research).  
Jeod -- GMLoader-Next improvements and Game Port.  
UnderminersTeam -- For the original [UTMT-CLI utility](https://github.com/UnderminersTeam/UndertaleModTool).  