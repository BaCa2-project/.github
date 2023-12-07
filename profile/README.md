<img src="baca2_logo.png" alt="BaCa2 Logo" width="200"/>

---

Welcome to the BaCa2 Project, a collaborative initiative aimed at building a comprehensive online system for creating programming tasks and automating the validation of submitted solutions. Our goal is to establish a robust platform that facilitates deep customization of testing and judging methods used to evaluate submitted solutions.

Currently developed for the [Institute of Computer Science and Mathematics](https://ii.uj.edu.pl/en_GB/start) at the Jagiellonian University in collaboration with [Dr. Grzegorz Gutowski](https://www.tcs.uj.edu.pl/gutowski) - leveraging his [kolejka](https://github.com/kolejka/kolejka) platform for testing task solutions.

---

## Project Overview

The BaCa2 Project is structured into three major components, each housed in a separate repository:

### 🌐 [BaCa2 Website](https://github.com/BaCa2-project/BaCa2)

BaCa2 website, powered by the Django framework, serves as the online platform for managing courses, creating tasks, and submitting solutions. The custom database routing module dynamically creates separate databases for new courses to prevent table bloating and facilitates routing between them. Integration with the USOS API will enable automatic assignment of users registered through the university system to appropriate courses.

### 📦 [BaCa2 Package Manager](https://github.com/BaCa2-project/BaCa2-package-manager)

The BaCa2 Package Manager is a PyPI package designed to interpret and work with packages representing tasks within the BaCa2 system.

### 🔄 [BaCa2 Broker](https://github.com/BaCa2-project/BaCa2-broker)

The BaCa2 Broker is a separate module dedicated to handling communication with the [kolejka](https://github.com/kolejka/kolejka) platform. This component ensures efficient and reliable interaction between the BaCa2 system and the task evaluation platform.

The modularity of the system is designed to facilitate extensibility and allow for the possibility of other systems plugging into the task checking module in the future.

## Contributors

The project is currently being developed by 3 students of Computer Science at the Jagiellonian University:

<div style="display: flex; align-items: center; margin: 0">
<img src="https://avatars.githubusercontent.com/u/71557281?v=4" title="bartosz-deptula" width="50" height="50" style="float: left; margin-right: 10px; border-radius: 50%" alt="bartosz-deptula-pfp"/>

[Bartosz Deptuła](https://github.com/ZyndramZM)<br>
**Role**: Responsible mainly for the package manager and broker modules, as well as parts of the BaCa2 website backend.
</div>

<div style="display: flex; align-items: center; margin: 0">
<img src="https://avatars.githubusercontent.com/u/89481714?v=4" title="mateusz-kadula" width="50" height="50" style="float: left; margin-right: 10px; border-radius: 50%" alt="mateusz-kadula-pfp"/>

[Mateusz Kadula](https://github.com/Matthew-1981)<br>
**Role**: Newest addition to the team, responsible for communication between BaCa2 website and broker module. Also, implementing customizable solution judging workflows.
</div>

<div style="display: flex; align-items: center; margin: 0">
<img src="https://avatars.githubusercontent.com/u/116686132?v=4" title="krzysztof-kalita" width="50" height="50" style="float: left; margin-right: 10px; border-radius: 50%" alt="krzysztof-kalita-pfp"/>

[Krzysztof Kalita](https://github.com/k-kalita)<br>
**Role**: Responsible for the BaCa2 website backend and frontend.
</div>

## License

The BaCa2 Project is licensed under the [GPL-3.0 license](LICENSE).

## Acknowledgments

We extend our gratitude to [Dr. Grzegorz Gutowski](https://www.tcs.uj.edu.pl/gutowski) for his collaboration and the [kolejka](https://github.com/kolejka/kolejka) platform without which this project could not have been created.

---

Feel free to explore each repository for more in-depth information about each component.
