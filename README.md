# PyGLM Wheels for PyPy

Pre-built Python wheels for PyGLM library on PyPy, patched for compatibility. Ideal for graphics and math operations in PyPy environments.

## Features
- Supports PyPy 3.9 on Windows amd64.
- Patched to fix CPython-specific issues like list access and imports.

## Installation
pip install --no-cache --only-binary ':all:' --find-links 'https://github.com/YOUR_GITHUB_USERNAME/pyglm-pypy/releases/tag/v2.8.2-pypy' 'pyglm==2.8.2' --no-index

## Usage
import glm
vec = glm.vec3(1, 2, 3)
print(vec)
