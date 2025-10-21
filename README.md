[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<br />
<p align="center">
  <a href="https://github.com/OpenArCloud/OSCP-Docs">
    <b style="font-size:24px">Open Spatial Computing Platform</b>
  </a>

  <h3 align="center">Getting Started with Open Spatial Computing Platform</h3>

  <p align="center">
    Learn how to integrate your code with the Open Spatial Computing Platform!
    <br />
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Open Spatial Computing Platform

The Open Spatial Computing Platform (OSCP) is a growing set of interoperable components that enable the authoring, publishing, discovery, and consumption of digital content anchored to the real world.

The components of the OSCP are open source, and our reference implementations provide examples so that others may integrate OSCP compatiblity into into their own applications.

Reference Components
* [GeoPose](https://www.ogc.org/projects/groups/geoposeswg)
* [Spatial Service Discovery](https://github.com/OpenArCloud/oscp-spatial-service-discovery)
* [Spatial Content Discovery](https://github.com/OpenArCloud/oscp-spatial-content-discovery)
* [WebXR reference client (spARcl)](https://openarcloud.github.io/sparcl/)

### Commercial Solutions

A growing number of commercial solutions are compatible with the OSCP. To quickly begin publishing digital content to the real world, consider using these:	
* [Augmented City](https://www.augmented.city/)
* [Immersal](https://immersal.com/)
* [XRMasters](https://xr-masters.com/)


<!-- GETTING STARTED -->
## Tutorial
We presented the OSCP in a comprehensive tutorial at Ubicomp 2025, you can find the materials in this folder: [2025_Ubicomp_tutorial](2025_Ubicomp_tutorial/2025_Ubicomp_tutorial.md)


## OSCP Sandbox Resources
Open AR Cloud and the Open Spatial Computing Platoform is not a commercial service, rather it is reference material intended to enable participation in an openly accessible, decentralized community of spatial content. However, we do run some 'sandbox' services for the the purpose of reference and learning.

Sandbox Spatial Service Discovery: [https://ssd.orbit-lab.org/](https://ssd.orbit-lab.org/), GUI via [Swagger](https://ssd.orbit-lab.org/swagger)

Sandbox Spatial Service Discovery: [https://scd.orbit-lab.org/](https://scd.orbit-lab.org/), GUI via [Swagger](https://scd.orbit-lab.org/swagger)

Sandbox Discovery Admin GUI: [https://oscp-admin.orbit-lab.org/](https://oscp-admin.orbit-lab.org/), login via Auth0 and Google

Sandbox WebXR client: [https://sparcl.orbit-lab.org/](https://sparcl.orbit-lab.org/), login via Auth0 and Google


## Simple Cloud Storage

In order to publish content to the Spatial Content Discovery Service, you must first upload your content (currently only GLB files are supported) to some publicly available hosting service. In the simplest case, this can be `github`, but better you run your own storage service, for which we provide an S3 Client (Amazon Simple Storage Service) Client. You can deploy this to AWS or host your own.

The code of the storage service is available here: [Simple Cloud Storage](https://github.com/OpenArCloud/simplecloudstorage)

## Visual Positioning

### Augmented City
* [AC Scanner](https://github.com/OpenArCloud/OSCP-Docs/blob/main/AugmentedCity/AC_Scanner_Tutorial.pdf)
* [AC Viewer](https://github.com/OpenArCloud/OSCP-Docs/blob/main/AugmentedCity/AC_Viewer_Tutorial.pdf)

### Immersal
* [City-scale demo](https://github.com/OpenArCloud/OSCP-Docs/blob/main/Immersal/Immersal_City_Scale_Demo.pdf)

### XR Masters
* [Placing AR Object using the XR-Masters App](https://github.com/OpenArCloud/OSCP-Docs/blob/main/XRMasters/XR_Masters_placement_tutorial.pdf)
* [Uploading to XR Masters](https://github.com/OpenArCloud/OSCP-Docs/blob/main/XRMasters/XR_Masters_Asset_Upload.md)
* [Uploading to Augmented City](https://github.com/OpenArCloud/OSCP-Docs/blob/main/XRMasters/XR_Masters_uploading_to_AugmentedCity.pdf)

### OpenVPS (from Nokia)
* [OpenVPS documentation](https://github.com/OpenArCloud/openvps)


<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/OpenArCloud/OSCP-Docs/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

[Alina Kadlubsky](mailto:communication@openarcloud.org)

[Gábor Sörös](https://github.com/soeroesg/)

Project Link: [https://github.com/OpenArCloud/OSCP-Docs](https://github.com/OpenArCloud/OSCP-Docs)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/OpenArCloud/OSCP-Docs.svg?style=for-the-badge
[contributors-url]: https://github.com/OpenArCloud/OSCP-Docs/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/OpenArCloud/OSCP-Docs.svg?style=for-the-badge
[forks-url]: https://github.com/OpenArCloud/OSCP-Docs/network/members
[stars-shield]: https://img.shields.io/github/stars/OpenArCloud/OSCP-Docs.svg?style=for-the-badge
[stars-url]: https://github.com/OpenArCloud/OSCP-Docs/stargazers
[issues-shield]: https://img.shields.io/github/issues/OpenArCloud/OSCP-Docs.svg?style=for-the-badge
[issues-url]: https://github.com/OpenArCloud/OSCP-Docs/issues
[license-shield]: https://img.shields.io/github/license/OpenArCloud/OSCP-Docs.svg?style=for-the-badge
[license-url]: https://github.com/OpenArCloud/OSCP-Docs/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/OpenArCloud
[product-screenshot]: images/screenshot.png
