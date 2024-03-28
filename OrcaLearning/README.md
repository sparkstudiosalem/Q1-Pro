# Orca Slicer

Orca Slicer is an open source fork of Bambu Studio, which originates from Prusa Slicer and Slic3r. It adds some software improvements, slicing algorythm enhancements, and multi-printer feature set, allowing more advanced slicing and native printer control

## Getting Started

Follow these steps to get started with Orca Slicer:

### Installation

* **Download**: Go to the [Orca Slicer GitHub Releases page](https://github.com/SoftFever/OrcaSlicer/releases) and download the appropriate installer for your operating system (Windows, macOS, Linux).

* **Install**: Follow the installation instructions provided with the installer. Orca Slicer comes with an intuitive installation wizard that guides you through the process.

* It is recommended to download the current [Official Release](https://github.com/SoftFever/OrcaSlicer/releases/latest), although they offer [Nightly Builds](https://github.com/SoftFever/OrcaSlicer/releases/tag/nightly-builds) with the latest features, also the latest bugs. The Release Candidate (RC) is also usually available

### Usage

1. Open OrcaSlicer, it can be found on the 3D-Printing Computer near the printers, or you may have elected to install it on your personal computer. The Icon is shown below.

  ![Orca Slicer Logo](ui_Elements/OrcaIcon.png)

1. Select which printer you intend to use from the Printers drop down located on the left top of the prepare tab.

   ![Printer Type](ui_Elements/PrinterType.png)

1. Select which Filament you intend to use from the Filament drop down located on the left of the prepare tab. The + button is for adding multiple filaments for a multicolor print on capable Printers.

   ![Filament Selection DropDown](ui_Elements/FilamentType.png)

1. Select the Printing Profile DropDown, They are usually named by their Layer Height, as well as the specific printing purpose (i.e. Fine, Draft, Strength).

   ![Printing Profile and Layer height DropDown](ui_Elements/Profile.png)

1. Import model(s) into the slicer by clicking the Add button on the top of the 3d view window. They can also be dragged in from file explorer or another program. OrcaSlicer accepts stl, Step, and 3mf file formats

   ![Model Import Button](ui_Elements/ImportModel.png)

1. Orient and arrange models automatically with the buttons at the top of the 3d view window. You may also elect to orient models manually by selecting "Lay on Face" and selecting a face of your model. Arrange will automatically arrange one or multiple models on your build plate(s)

  ![Audomatic Orient and Arrange](ui_Elements/OrientArrange.png)

1. After your Printer, Filament, Profile, and Models have been selected and setup, you can click "Slice Plate" at the top right of the window. This will change to a gcode view of your model and color coded paths for Line Types.
2. The Slider on the right can be dragged up and down to show each layer line by line.

![Sliced View](ui_Elements/Slicing_Sending.png)

1. You may access the selected printer's web interface by selecting the devide tab along the top of the window. For OctoPrint and Klipper this will just mirror what the browser view shows, allowing for easy configuration and printer monitoring.

![Device Tab](ui_Elements/Device.png)

1. Paramaters can be different for each model imported. The selector switch is labeled "Global/Objects" shown below. Selecting "Objects" allows you to change individual settings for each model (i.e. infill percentage, wall counts, layer height, etc.)

![Objects / Global Selector](ui_Elements/Objects.png)

Selecting each model by name presents the available settings for each. Best practice is to select a printing profile to start with before you select the "Objects" tab.

![Object View](ui_Elements/Objects2.png)

1. For users looking for more in-depth settings, they may choose to turn on "Advanced" settings just to the right of the Global / Objects Selector. It will add new settings tabs, as well as populate more settings in each.

![Advanced Selector](ui_Elements/Advanced.png)

### Resources

- **Documentation**: Refer to the [official documentation](https://orca-docs.readthedocs.io/en/latest/) for detailed information on how to use Orca Slicer effectively.
  
- **Tutorials**: Many great tutorials on why and how to use OrcaSlicer are available. Michael Law of [TeachingTech](https://www.youtube.com/watch?v=cquTCpz1V74) on YouTube has a great video. There's also an amazing write up on the [Obico Blog](https://www.obico.io/blog/orcaslicer/) by Pranav G. 

- **Community**: Join the [OrcaSlicer Discord group](https://discord.gg/P4VE9UY9gJ) to connect with other users, ask questions, and share your experiences.

### Contributing

Contributions to Orca Slicer are welcome! Whether you want to report a bug, suggest a new feature, or contribute code, please refer to the [GitHub Issues](https://github.com/SoftFever/OrcaSlicer/issues) for more information.

## License

Orca Slicer is licensed under the GNU Affero General Public License, version 3. Orca Slicer is based on Bambu Studio by BambuLab. Please review the license terms before using Orca Slicer in your projects.

## Support

For any questions, issues, or feedback, please [open an issue](https://github.com/OrcaSlicer/Orca/issues) on GitHub or ask for help on the official [OrcaSlicer Discord group](https://discord.gg/P4VE9UY9gJ)