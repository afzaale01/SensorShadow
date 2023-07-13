# SensorShadow Class for Cesium
This repository contains the `SensorShadow` class for Cesium.js, a JavaScript library for creating 3D maps and globes in a web browser. The `SensorShadow` class allows you to create, update, and manage sensor shadow entities, including sensor shadow visualization, color coding, frustum support, and many more.

## Screenshot

<img src="https://github.com/DigitalArsenal/SensorShadow/assets/749096/a3c64e59-d815-4d15-b1bd-cc7d9d8cc59d" width="40%" />

## Demo

[Sandcastle Link]([https://sandcastle.cesium.com/#c=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](https://sandcastle.cesium.com/#c=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)https://sandcastle.cesium.com/#c=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](https://sandcastle.cesium.com/#c=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)https://sandcastle.cesium.com/#c=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)

## Installation

This class requires the Cesium.js library. You need to install Cesium.js and import the SensorShadow class into your project.

Please refer to the official [Cesium.js Installation Guide](https://cesium.com/docs/tutorials/quick-start/) for more information on how to install and set up Cesium.js.

## Usage

To create a new SensorShadow instance, you need a reference to the Cesium viewer instance and an optional configuration object. The configuration object can include various properties like `cameraPosition`, `viewPosition`, `viewAreaColor`, `shadowAreaColor`, `alpha`, `frustum`, `size` and `depthBias`.

Below is an example of how to create a new SensorShadow instance:

```javascript
let sensorShadow = new SensorShadow(viewer, {
  cameraPosition: new Cartesian3(0, 0, 0),
  viewPosition: new Cartesian3(1, 1, 1),
  viewAreaColor: new Color(0, 1, 0),
  shadowAreaColor: new Color(1, 0, 0),
  alpha: 0.5,
  frustum: true,
  size: 512,
});
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. Please make sure to update tests as appropriate.

## License

### [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/)
