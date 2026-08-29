# Liar/Xixinb - Open Source Toolbox Engine

This project is licensed under the GNU Affero General Public License v3 (AGPL3).
See [LICENSE](LICENSE) for the full license text.

## Project Structure

```
Liar/
├── Depend/          # Dependency bridge implementations
├── Engine/          # Application engine layer
│   ├── android/     # Flutter Android host
│   ├── lib/         # Dart core library
│   ├── platform_impl/  # Platform-specific Kotlin implementation
│   └── ...
├── Kernel/          # Native C++ kernel
│   ├── lib/         # Libraries and tool implementations
│   │   
│   └── Liar/   
│   └── Xixinb/        # Format tool modules
├── Configuration/  # JSON configuration files
├── Script/          # Script definitions and execution
└── LICENSE          # AGPL3
```

## Building

This project uses a non-standard build layout. Manual configuration of
CMake and Gradle paths is required. Refer to individual CMakeLists.txt
files for native build targets and Kotlin/ for Android integration.

## License

Copyright (C) 2024 xixi5522

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published
by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
