#!/usr/bin/env python3
"""
Unit tests for emotion_detection module
"""
import unittest
from EmotionDetection import emotion_detector


class TestEmotionDetection(unittest.TestCase):
    """Test cases for the emotion_detector function"""

    def test_joy(self):
        """Test statement that should return joy as dominant emotion"""
        statement = "I am glad this happened"
        result = emotion_detector(statement)
        self.assertEqual(result['dominant_emotion'], 'joy')

    def test_anger(self):
        """Test statement that should return anger as dominant emotion"""
        statement = "I am really mad about this"
        result = emotion_detector(statement)
        self.assertEqual(result['dominant_emotion'], 'anger')

    def test_disgust(self):
        """Test statement that should return disgust as dominant emotion"""
        statement = "I feel disgusted just hearing about this"
        result = emotion_detector(statement)
        self.assertEqual(result['dominant_emotion'], 'disgust')

    def test_sadness(self):
        """Test statement that should return sadness as dominant emotion"""
        statement = "I am so sad about this"
        result = emotion_detector(statement)
        self.assertEqual(result['dominant_emotion'], 'sadness')

    def test_fear(self):
        """Test statement that should return fear as dominant emotion"""
        statement = "I am really afraid that this will happen"
        result = emotion_detector(statement)
        self.assertEqual(result['dominant_emotion'], 'fear')


if __name__ == '__main__':
    unittest.main()
