# Model Installation Instructions

## How to Add Your CNN Model

1. **Replace the placeholder file**:
   - Delete the `model.tflite` placeholder file
   - Copy your actual .tflite model file here
   - Ensure it's named exactly `model.tflite`

2. **Model Requirements**:
   - Format: TensorFlow Lite (.tflite)
   - Input: 224x224 RGB images
   - Output: Float array with [probability, confidence_score]
   - Expected output format: [0.0-1.0 probability, 0.0-1.0 confidence]

3. **Testing Your Model**:
   - Build and run the app
   - Test with sample images
   - Verify predictions match expected results

## Model Training Notes
- Model should be trained specifically for jaundice detection in children
- Consider lighting variations and skin tone differences
- Include data augmentation for robustness
- Validate with medical professionals

## Support
For model integration issues, refer to the main README.md file or contact development team.
