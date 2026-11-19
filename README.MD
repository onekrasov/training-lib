# Training Library

This repo contains structured workouts that can be used in Intervals.icu or adopted to other platforms if needed.

## Structure

- [**events/**](events/README.md): Event-specific training plans with weekly structure and phases
  - [Mallorca 312](events/mallorca-312.md) - 16-week plan for 312km cycling event
  - [Olympic Triathlon](events/olympic-triathlon.md) - 12-week plan for Olympic distance triathlon
  - [Oceanman 5K](events/oceanman-5k.md) - 8-week minimal plan for 5km open water swim (1-2 swims/week)
  - [Oceanman 10K](events/oceanman-10k.md) - 14-week plan for 10km open water swim
- **sports/**: Structured workout library organized by sport (see below)
- [**TRAINING-GUIDE.md**](TRAINING-GUIDE.md): Complete guide on how to use this library
- [**TSS-REFERENCE.md**](TSS-REFERENCE.md): TSS (Training Stress Score) explanation and planning guide

## File Naming Convention

All workout files are prefixed with their TSS (Training Stress Score) for easy load planning:
- Example: `88-sweetspot-2x20.icu` = 88 TSS workout
- Use TSS to plan weekly training load (see TSS-REFERENCE.md)

## Quick Start

1. Choose your event: [Mallorca 312](events/mallorca-312.md) | [Olympic Triathlon](events/olympic-triathlon.md) | [Oceanman 5K](events/oceanman-5k.md) | [Oceanman 10K](events/oceanman-10k.md)
2. Browse workouts by sport below
3. Read [TRAINING-GUIDE.md](TRAINING-GUIDE.md) for zone explanations and best practices
4. Use [TSS-REFERENCE.md](TSS-REFERENCE.md) to plan your weekly training load

## Workout Library

### 🚴 Cycling Workouts

#### Recovery & Endurance
- [32-recovery-ride.icu](sports/bike/32-recovery-ride.icu) - **32 TSS** | 1h active recovery
- [125-endurance-3h.icu](sports/bike/125-endurance-3h.icu) - **125 TSS** | 3h aerobic endurance
- [165-long-endurance-4h.icu](sports/bike/165-long-endurance-4h.icu) - **165 TSS** | 4h long ride
- [205-long-endurance-5h.icu](sports/bike/205-long-endurance-5h.icu) - **205 TSS** | 5h long ride

#### Threshold & Tempo
- [88-sweetspot-2x20.icu](sports/bike/88-sweetspot-2x20.icu) - **88 TSS** | Classic 2x20min sweetspot
- [72-threshold-intervals.icu](sports/bike/72-threshold-intervals.icu) - **72 TSS** | 2x20min threshold
- [82-over-unders.icu](sports/bike/82-over-unders.icu) - **82 TSS** | Threshold pacing intervals
- [115-climbing-repeats.icu](sports/bike/115-climbing-repeats.icu) - **115 TSS** | 5x15min climbing power
- [165-race-simulation.icu](sports/bike/165-race-simulation.icu) - **165 TSS** | 3x40min race pace

#### High Intensity
- [60-norwegian-4x4.icu](sports/bike/60-norwegian-4x4.icu) - **60 TSS** | 4x4min VO2max intervals
- [78-vo2max-intervals.icu](sports/bike/78-vo2max-intervals.icu) - **78 TSS** | 5x5min VO2max

### 🏃 Running Workouts

#### Easy & Endurance
- [42-easy-run-45m.icu](sports/run/42-easy-run-45m.icu) - **42 TSS** | 45min easy/recovery run
- [88-long-run-90m.icu](sports/run/88-long-run-90m.icu) - **88 TSS** | 90min long run

#### Threshold & Tempo
- [48-tempo-run.icu](sports/run/48-tempo-run.icu) - **48 TSS** | 20min continuous tempo
- [62-threshold-intervals-5x1k.icu](sports/run/62-threshold-intervals-5x1k.icu) - **62 TSS** | 5x5min threshold
- [68-race-pace-intervals.icu](sports/run/68-race-pace-intervals.icu) - **68 TSS** | 4x8min race pace

#### High Intensity
- [68-vo2max-intervals-6x800.icu](sports/run/68-vo2max-intervals-6x800.icu) - **68 TSS** | 6x4min VO2max

#### Triathlon Specific
- [42-brick-run-30m.icu](sports/run/42-brick-run-30m.icu) - **42 TSS** | 30min run off the bike

### 🏊 Swimming Workouts

#### Technique & Speed
- [75-technique-drills.icu](sports/swim/75-technique-drills.icu) - **75 TSS** | ~2000m technique & drills
- [105-speed-intervals.icu](sports/swim/105-speed-intervals.icu) - **105 TSS** | ~2000m speed work

#### Threshold & Race Pace
- [125-threshold-intervals.icu](sports/swim/125-threshold-intervals.icu) - **125 TSS** | ~2400m threshold (6x300m)
- [135-race-pace-1500m.icu](sports/swim/135-race-pace-1500m.icu) - **135 TSS** | ~2300m race pace (3x500m)
- [165-threshold-long-intervals.icu](sports/swim/165-threshold-long-intervals.icu) - **165 TSS** | ~3600m threshold (6x500m)
- [175-threshold-750m-intervals.icu](sports/swim/175-threshold-750m-intervals.icu) - **175 TSS** | ~4000m threshold (4x750m)

#### Endurance (Pool)
- [145-endurance-3000m.icu](sports/swim/145-endurance-3000m.icu) - **145 TSS** | 3000m aerobic endurance
- [185-endurance-4000m.icu](sports/swim/185-endurance-4000m.icu) - **185 TSS** | 4000m endurance
- [225-endurance-5000m.icu](sports/swim/225-endurance-5000m.icu) - **225 TSS** | 5000m endurance
- [265-endurance-6000m.icu](sports/swim/265-endurance-6000m.icu) - **265 TSS** | 6000m endurance
- [340-endurance-8000m.icu](sports/swim/340-endurance-8000m.icu) - **340 TSS** | 8000m endurance
- [420-endurance-10000m.icu](sports/swim/420-endurance-10000m.icu) - **420 TSS** | 10000m endurance

#### Open Water Specific
- [155-openwater-simulation-3500m.icu](sports/swim/155-openwater-simulation-3500m.icu) - **155 TSS** | 3x1000m continuous (sighting practice)
- [195-openwater-simulation-4500m.icu](sports/swim/195-openwater-simulation-4500m.icu) - **195 TSS** | 4x1000m continuous (sighting practice)
- [205-tempo-continuous-5000m.icu](sports/swim/205-tempo-continuous-5000m.icu) - **205 TSS** | 3500m continuous tempo
- [245-tempo-continuous-6000m.icu](sports/swim/245-tempo-continuous-6000m.icu) - **245 TSS** | 4000m continuous tempo

## TSS Categories

**Recovery**: 0-40 TSS | **Easy**: 40-70 TSS | **Moderate**: 70-120 TSS | **Hard**: 120-180 TSS | **Very Hard**: 180-250+ TSS
