// Copyright (c) 2022 8th Wall, Inc.
//
// app.js is the main entry point for your 8th Wall app. Code here will execute after head.html
// is loaded, and before body.html is loaded.

import './main.css'

import {tapPlaySound} from './tap-to-play-sound'
AFRAME.registerComponent('tap-play-sound', tapPlaySound)

import {splashScreenComponent} from './components/splash-screen'
AFRAME.registerComponent('splash-screen', splashScreenComponent)

import {onboardingComponent} from './components/onboarding'
AFRAME.registerComponent('onboarding', onboardingComponent)

AFRAME.registerComponent('audiohandler', {
  init() {
    console.log('init')
    let playing = false
    const audio = document.querySelector('#soup')
    this.el.addEventListener('click', () => {
      if (!playing) {
        audio.play()
      } else {
        audio.pause()
        audio.currentTime = 0
      }
      playing = !playing
    })
  },
})

// zanimation__pos="property: position; dur: 1000; easing: easeInOutSine; loop: false; from: 0 0 -1; to: 0 0 0"
// zanimation__scale="property: scale; dir: alternate; dur: 1000; easing: easeInOutSine; loop: false; from: .5 .5 .5; to: .5 .5 .5"
// zanimation__rotation="property: rotation; to: 0 360 0 ; loop: true; dur: 10000"
AFRAME.registerComponent('animation-manager', {
  init() {
    console.log('init')
    this.el.sceneEl.addEventListener('xrimagefound', () => {
      console.log('found')

      this.el.setAttribute('animation__pos', 'property: position; dur: 1000; easing: easeInOutSine; loop: false; from: 0 0 0; to: 0 .50 0')
      this.el.setAttribute('animation__scale', 'property: scale; dir: alternate; dur: 1000; easing: easeInOutSine; loop: false; from: 0.5 0.5 0.5; to: .8 .8 .8')
      this.el.addEventListener('animationcomplete__pos', () => {
        console.log('animation complete, start spinning')
        // this.el.setAttribute('position', '0.5 0 0')
        this.el.setAttribute('scale', '.8 .8 .8')
         this.el.setAttribute('animation__rotation', 'property: rotation; to: 0 360 0 ; loop: true; dur: 10000')
      })
    })

    this.el.sceneEl.addEventListener('xrimagelost', () => {
      console.log('lost')
      this.el.removeAttribute('animation__pos')
      this.el.removeAttribute('animation__scale')
      this.el.removeAttribute('animation__rotation')
    })
  },
})
