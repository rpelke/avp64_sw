##############################################################################
#                                                                            #
# Copyright 2020 Lukas Jünger                                                #
#                                                                            #
# Licensed under the Apache License, Version 2.0 (the "License");            #
# you may not use this file except in compliance with the License.           #
# You may obtain a copy of the License at                                    #
#                                                                            #
#     http://www.apache.org/licenses/LICENSE-2.0                             #
#                                                                            #
# Unless required by applicable law or agreed to in writing, software        #
# distributed under the License is distributed on an "AS IS" BASIS,          #
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.   #
# See the License for the specific language governing permissions and        #
# limitations under the License.                                             #
#                                                                            #
##############################################################################

FROM ubuntu:bionic
WORKDIR /app
RUN apt-get update \
	&& apt-get -y install build-essential \
	libncurses-dev \
	file \
	wget \
	cpio \
	python \
	unzip \
	rsync \
	bc \
	git \
	libssl-dev \
	device-tree-compiler \
	gcc-aarch64-linux-gnu 
ENTRYPOINT ["/app/docker_entrypoint.sh"]
