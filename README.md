# diskimage-builder-elements
Custom elements for Diskimage-builder (https://github.com/openstack/diskimage-builder).

This repository contains diskimage-builder elements DreamCompute (https://cloud.dreamhost.com/) uses to build public images.
These elements should either be copied into the 'elements' directory in diskimage-builder's elements directory or referenced
by setting the environment variable "ELEMENTS_PATH" when calling `disk-image-create`.
