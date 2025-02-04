# Boards

## Legend

### Compatibility

| Icon                | Meaning               |
| ------------------- | --------------------- |
| :white_check_mark:  | Fully compatible      |
| :warning:           | Partial compatibility |
| :x:                 | Not compatible        |
| :hammer_and_wrench: | In progress           |
| :grey_question:     | Unknown               |

### Support

| Icon       | Meaning                                                                                                    |
| ---------- | ---------------------------------------------------------------------------------------------------------- |
| :rocket:   | Supported by [:rocket: OpenShock maintainers](https://github.com/orgs/OpenShock/teams/maintainer)          |
| :airplane: | Supported by [:airplane: Community maintainers](https://github.com/OpenShock/Firmware/graphs/contributors) |

### Features

| Icon    | Meaning                                    |
| ------- | ------------------------------------------ |
| :cloud: | Supports over-the-air updating             |
| :lock:  | Supports hardware accelerated cryptography |

## Fully maintained

These boards are tested before every release by the [:rocket: OpenShock maintainers](https://github.com/orgs/OpenShock/teams/maintainer).

| Board                                              | Variant | Labels                            | Maintainer(s)                                          |
| -------------------------------------------------- | ------- | --------------------------------- | ------------------------------------------------------ |
| [PiShock (2023)](pishock/2023-pishock.md)          | All     | :white_check_mark:                | [:rocket: Red Mushie](https://github.com/redmushie)    |
| [PiShock Lite (2021 Q3)](pishock/2021q3-lite.md)   | All     | :white_check_mark:                | [:rocket: HentaiHeaven](https://github.com/hhvrc)      |
| [Seeed Studio Xiao ESP32S3](seeed/xiao-esp32s3.md) | All     | :white_check_mark: :cloud: :lock: | [:rocket: Red Mushie](https://github.com/redmushie)    |
| [Wemos D1 Mini ESP32](wemos/d1-mini-esp32.md)      | All     | :white_check_mark:                | [:rocket: HentaiHeaven](https://github.com/hhvrc)      |
| [Wemos Lolin S3](wemos/lolin-s3.md)                | All     | :white_check_mark: :cloud: :lock: | [:rocket: Red Mushie](https://github.com/redmushie)    |
| [OpenShock Core V1](openshock/core-v1.md)          | All     | :white_check_mark: :cloud: :lock: | [:rocket: nullstalgia](https://github.com/nullstalgia) |
| [OpenShock Core V2](openshock/core-v2.md)          | All     | :white_check_mark: :cloud: :lock: | [:rocket: nullstalgia](https://github.com/nullstalgia) |

## Community maintained

These boards are supported by designated [:airplane: Community maintainers](https://github.com/OpenShock/Firmware/graphs/contributors).

We do our best to give these contributors sufficient time to test new firmware during the release candidate phase(s), but we cannot guarantee that they got around to a full test cycle prior to a new release.

| Board                                                          | Variant       | Labels                     | Maintainer(s)                                          |
| -------------------------------------------------------------- | ------------- | -------------------------- | ------------------------------------------------------ |
| [DFRobot FireBeetle ESP32-E](dfr-firebeetle/dfr-firebeetle.md) | ESP32-E (All) | :white_check_mark: :cloud: | [:airplane: LostQuasar](https://github.com/LostQuasar) |

## Not maintained

These boards are untested and not maintained. They might work, but no guarantees.

| Compatibility           | Board                                             | Variant | Labels         |
| ----------------------- | ------------------------------------------------- | ------- | -------------- |
| :grey_question: Unknown | [Knockoff ESP32-S3 "Dorx"](china/esp32s3-dorx.md) | R8N2    | :lock: |

## Avoid :x:

These boards have been reported to have issues with OpenShock.

| Board                                         | Variant    | Reason                      | Date Added | Labels  |
| --------------------------------------------- | ---------- | --------------------------- | ---------- | ------- |
| [Wemos Lolin S2 Mini](wemos/lolin-s2-mini.md) | N4R2 (All) | WiFi & Internet instability | 17.11.2024 | :cloud: |

## Incompatible :x:

These boards are fundamentally incompatible with OpenShock.

| Board                                            | Reason                |
| ------------------------------------------------ | --------------------- |
| [PiShock Plus (2021 Q1)](pishock/2021q1-plus.md) | Uses incompatible SoC |
