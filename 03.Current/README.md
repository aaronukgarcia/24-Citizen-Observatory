# On This Night

*A population-scale smartphone sky observatory — and what it can honestly do. Concept paper, v2.0, August 2026.*

## The idea

Once a year, at one agreed instant, millions of people point their phones at the sky and take a photograph. What can be done with the combined result?

## The honest answer

**This is a concept paper — nothing built, nothing run, no one contacted.** And the answer is narrower than the idea first suggests:

- **It is *not* a "synthetic aperture telescope."** That would need phase precision of ~10 nanometres; phones give metre-scale GPS and millisecond-scale timing — a mismatch of 6–8 orders of magnitude, fundamental physics. The original framing is dropped entirely.
- **Stacking works for co-located crowds.** Combine N images of the *same* patch of sky and noise averages down as √N — a stadium of 90,000 phones stacks to ~300× cleaner. But people spread across the globe each see a *different* sky, so their images **cannot** be co-added into one deep picture. The global dataset's value is simultaneous *coverage*, not depth. Conflating the two is the easiest way to oversell this, and v2 doesn't.
- **It is not first.** [Unistellar's network](https://www.seti.org/projects/unistellar-network/) (with SETI and NASA) already coordinates simultaneous citizen observations, stacks them into composite super-images, and has published DART results in *Nature*. Coordinated citizen stacking is not new. This paper credits that as prior art, not as a partner.

## Where the real, narrower novelty lives

Not aperture — **distribution**. Unistellar uses ~25,000 dedicated ~£2,000 smart telescopes; this proposes the phone already in your pocket, at population scale. That enables things a fleet of telescopes cannot: **space-debris parallax** (observers hundreds of km apart triangulate a low-orbit object's 3D position), **atmospheric tomography** (millions of simultaneous sightlines — with real precedent in [Semeter's smartphone-GNSS ionosphere work](https://ui.adsabs.harvard.edu/abs/2024nsf....2428531S/abstract)), and **transient detection** with redundant global coverage.

## The first test

A small pilot with a few thousand committed participants, with pre-committed pass/fail: does a co-located subset stack to the predicted √N SNR on a known star field? Can the distributed subset triangulate a catalogued satellite's orbit? If not, the premise is wrong and the project stops there — cheaply.

## Documentation

See [`On_This_Night_v2.pdf`](On_This_Night_v2.pdf).

## What would help

An astronomer or citizen-science group willing to run one coordinated capture and check whether the stacking and parallax deliver what the physics predicts. A negative result is worth knowing.

## License

MIT License — see [LICENSE](LICENSE).

## Contact

Aaron Garcia
aaron@garcia.ltd
