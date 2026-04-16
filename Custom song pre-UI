#Paranoid by Black Sabbath
use_bpm 167
intro_notes = [:E3, :E3, :E3, :E3, :G3, :A4, :B4, :E3, :G3, :A4, :B4]
intro_sleeps = [1.5, 1.5, 1, 0.5, 0.5, 0.5, 0.5, 0.5, 0.5, 0.5, 0.5]
repulsor_sound = "C:/Users/mario_restori/Desktop/Repulsor Blast (Iron Man) - Sound Effect for editing.mp3"
tony_talk = "C:/Users/mario_restori/Documents/Audacity/Avengers Angry Argument Scene - The Avengers 2012 movie scene.wav"
can_you = "C:/Users/mario_restori/Documents/Audacity/can_you.wav"
and_i ="C:/Users/mario_restori/Documents/Audacity/final...i...amironman.mp3.wav"
define :play_note do |note, time|
  use_synth :pluck
  play note
  sleep time
end
define :guitar_solo do
  play :g4, amp: 0.15
  sleep 0.7
  play :b4, amp: 0.15
  sleep 0.7
  play :g4, amp: 0.15
  sleep 3
  play :g4, amp: 0.15
  sleep 0.7
  play :g4, amp: 0.15
  sleep 0.7
  play :a4, amp: 0.15
  sleep 0.7
  play :e4, amp: 0.15
  sleep 0.7
  play :e4, amp: 0.15
  sleep 0.7
  play :b4, amp: 0.15
  sleep 0.7
  play :g4, amp: 0.15
  sleep 0.7
  play :a4, amp: 0.15
  sleep 1
  play :e4, amp: 0.15
  sleep 0.7
  play :g4, amp: 0.15
  sleep 0.6
  play :d4, amp: 0.15
  sleep 1
  play :e4, amp: 0.15
  sleep 0.7
end
define :main_melody do
  play :g4
  sleep 0.6
  play :g4
  sleep 0.6
  play :g4
  sleep 0.6
  play :g4
  sleep 0.6
  play :g4
  sleep 1
  play :e4
  sleep 0.75
  play :e4
  sleep 0.75
  play :e4
  sleep 1
  play :d4
  sleep 0.6
  play :d4
  sleep 0.6
  play :d4
  sleep 0.6
  play :e4
  sleep 1.5
  play :g4
  sleep 0.6
  play :d4
  sleep 1
  play :e4
  sleep 2
end
define :guitar_rift do
  use_synth :pluck
  play :b4, amp: 2
  sleep 4
  play :g4, amp: 2
  sleep 2
  play :a4, amp: 2
  sleep 1.5
end
sample and_i, amp: 3
sleep 30
2.times do
  i = 0
  11.times do
    play_note intro_notes[i], intro_sleeps[i]
    i = i + 1
  end
end

live_loop :drums do
  124.times do
    sample :drum_heavy_kick, amp: 0.75
    sleep 1
    sample :drum_snare_hard, amp: 0.75
    sleep 1
  end
  stop
end
2.times do
  i = 0
  11.times do
    play_note intro_notes[i], intro_sleeps[i]
    i = i + 1
  end
end
2.times do
  main_melody
end
guitar_rift
sample repulsor_sound
sleep 6
guitar_rift
sleep 6
2.times do
  main_melody
end
sleep 0.7
sample can_you, amp: 2
2.times do
  guitar_rift
  sleep 8
end
2.times do
  main_melody
end
sample tony_talk, amp: 5
4.times do
  guitar_solo
end
2.times do
  main_melody
end
play :g4
sleep 0.6
play :g4
sleep 0.6
play :g4
sleep 0.6
play :g4
sleep 0.6
play :g4
sleep 1
play :e4
sleep 0.75
play :e4
sleep 0.75
play :e4
sleep 1
play :d4
sleep 0.6
play :d4
sleep 0.6
play :d4
sleep 0.6
play :e4
sleep 1.5
play :g4
sleep 0.6
play :b4
sleep 1
play :c4
sleep 0.85
play :c4, amp: 0.75
sleep 0.85
play :c4, amp: 0.5
sleep 0.85
play :c4, amp: 0.25
sleep 0.85
play :c4, amp: 0.05
