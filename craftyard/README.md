# Astrocosmos Craftyard

Welcome to the Astrocosmos Craftyard!

a massive factory located in a planet in the Tarteeb planetary system!. Some of the best architects and engineer of the cosmos are contributing here. 

**README!**
- [Craftyard Contents](#Craftward_Contents)
- [Schematic Tutorials](#Schematic_Tutorials)
- [Ship Tutorials](#Ship_Tutorials)
- [Making your Own Ship](#Making_your_Own_Ship)
- [Known Problems](#Known_Problems)


# Craftyard Contents

The detailed craftyard contents can be seen in the production-list.csv in the same folder, [here!](./production-list.csv). The list contains data of producers, their products, product's nickname, product type, and current mark to identify each product from others. Those then followed by length, width, height, and mass to identify the size and volume. After that maximum crew and weight for the product's capacity, followed by top speed, accelaration, roll, pitch, and yaw for movement data.

# Schematic Tutorials

WIP

# Ship Controls Tutorials

WIP

Shao's how to: https://discord.com/channels/244934352092397568/1307104773471731792

# Making your Own Ship

WIP

Clockwork tutorial: https://youtu.be/K1G3xlKYMjQ?si=VcAVerIWeqiOpoYt

# Known Problems

- If there's a crash with problem "ticking", you may need to install/activate Neruina mod

## Schematic Problems
- If your schematic pasted uncomplete, and there's warning:
    > "Schematic had 0000 fatal errors
      
    Then, you may need to acces the world folder and find the VMod config folder located in /serverconfig. In the config file, you will find:
    ```
    ...
    [VModConfig.Schematics]
	#No Comment
	#Range: > 0
	TIMEOUT_TIME = 250
    ...
    ```
    Change the TIMEOUT_TIME value, while the value must be greater than zero.

    > [!WARNING]  
    > This might need more allocated RAM

- If you were pasting schematic, and then suddenly crashed with the problem "ticking"  

    Then, you may need to change you may need to acces the world folder and find the VMod config folder located in /serverconfig. In the config file, you will find:
    ```
    ...
    [VModConfig.Schematics]
    ...
	#Allows ships to be created over several ticks (so that if you have a huge ship it won't freeze server). May be incompatible with some mods though.
	ALLOW_CHUNK_PLACEMENT_INTERRUPTION = false
	#Allows ships to be updated over several ticks (so that if you have a huge ship it won't freeze server). May be incompatible with some mods though.
	ALLOW_CHUNK_UPDATE_INTERRUPTION = false
    ...
    ``` 
    Change `ALLOW_CHUNK_PLACEMENT_INTERRUPTION` and `ALLOW_CHUNK_UPDATE_INTERRUPTION` from true to false

    > [!WARNING]  
    > This might need more allocated RAM

## Ship Problems

## Cosmic Horizon Problems (and Starlance)
- Clockwork tab not opening:      
Install Architectury api.

- Cosmic Horizons 0.0.7.3 not working on mac:  
It's a bug, use 0.0.7.2 instead.

- Valkyrien Skies and/or Starlance not loading:  
Make sure that Kotlin for Forge and Cosmic Horizons are installed.

- Cosmic Horizons not working with Rubidium or Optifine:  
Use Embeddium instead.

- Starlance ships not going back into planets:  
Update starlance to latest version.

- Starlance/Valkyrien Skies crashes with std:system_error:  
If you're using a server host, switch to another one. If you are self hosting, don't use pterodactyl.

- Starlance/VS2 ship gets stuck at world height:  
Double or triple the lodDetail configuration in vscore configs.

- White floor in space with distant horizons:  
Go to the DH config file and search for "ignoredRenderBlockCsv" and add cosmos:height_limiter to it.

- Unable to see planets when far away from them:  
Remove Tallyho and/or Simple Clouds

- Unable to interact with blocks after giving them physics:  
Downgrade forge to 47.4.0


