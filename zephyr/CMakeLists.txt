# Copyright (c) 2026 Jonathan Elliot Peace <jep@alphabetiq.com>
# SPDX-License-Identifier: Apache-2.0

# hal_broadcom is a Zephyr blob-only HAL module. It carries no source
# of its own; its purpose is to host upstream-fetched firmware blobs
# (currently brcmfmac43436s-sdio.{bin,txt}) for drivers that need
# them at runtime. The driver references the blob paths via
# ${ZEPHYR_HAL_BROADCOM_MODULE_DIR}/zephyr/blobs/...
