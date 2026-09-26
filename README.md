# 🌱 Sustainable AI Data Centres

### Exploring ways to reduce heat, water consumption and energy-related emissions

## 📌 Overview

Artificial Intelligence is growing rapidly, and AI workloads require powerful computing infrastructure. Data centres use GPUs and other high-performance hardware to run AI models, which increases electricity demand and generates heat.

This case study explores a simple question:

> **How can we continue developing AI while making the infrastructure behind it more energy- and water-efficient?**

Instead of focusing only on reducing AI usage, this case study looks at infrastructure-level solutions such as efficient computing, liquid cooling, renewable electricity, cold-climate operation and waste-heat recovery.

---

## 1. 🔥 The Core Problem

AI workloads require high-performance computing hardware.

The basic chain is:

**AI Workload → GPU → Electricity → Heat → Cooling**

More AI infrastructure can therefore create challenges around:

* Electricity demand
* Heat management
* Cooling requirements
* Water consumption in some cooling systems
* Emissions associated with electricity generation

The International Energy Agency (IEA) estimates that data centres accounted for around **180 million tonnes (Mt) of indirect CO₂ emissions from electricity use in 2024**. In its Base Case, this could rise to around **300 Mt by 2035**. These figures cover data centres as a whole, not AI alone.
[Source: IEA – Energy and AI](https://www.iea.org/reports/energy-and-ai)

---

## 2. 🧠 What is a GPU?

A **GPU (Graphics Processing Unit)** is a type of processor designed to perform many calculations in parallel.

Although GPUs were originally developed mainly for graphics, their parallel-processing capabilities make them highly useful for:

* AI model training
* Machine learning
* AI inference
* Scientific computing
* High-performance computing

High-performance GPU workloads generate significant heat, so effective cooling becomes important.

---

## 3. ❄️ Why Cooling Matters

Computing hardware produces heat while operating.

If this heat is not removed effectively, it can affect system performance, reliability and operating conditions.

Data centres can use different cooling approaches, including:

### Air Cooling 🌬️

Uses fans and airflow to move heat away from IT equipment.

### Liquid Cooling 💧

Uses liquid to transfer heat away from high-density computing hardware.

Liquid can carry heat more effectively than air, which makes liquid cooling particularly relevant for high-density computing environments.

---

## 4. ♻️ Closed-Loop Liquid Cooling

One approach to reducing water consumption is **closed-loop liquid cooling**.

A simplified system can be represented as:

**GPU → Coolant → Heat Exchanger → Heat Rejection → Coolant Returns**

The coolant circulates repeatedly rather than being continuously replaced with fresh water.

This can significantly reduce ongoing water consumption compared with cooling approaches that rely heavily on evaporation.

However:

> **Closed-loop cooling does not automatically mean zero water consumption.**

Water or coolant may still be required for maintenance, system losses or other parts of the overall cooling infrastructure.

The U.S. Department of Energy describes direct liquid-cooling systems in which heat from IT equipment is transferred to a recirculating chilled-water loop.
[Source: U.S. Department of Energy](https://www.energy.gov/cmei/femp/cooling-water-efficiency-opportunities-federal-data-centers)

---

## 5. ⚡ Renewable Electricity

Cooling is only one part of the sustainability challenge.

AI data centres also require large amounts of electricity.

Electricity can come from different sources, including:

* ☀️ Solar
* 🌬️ Wind
* 💧 Hydropower
* ⚛️ Nuclear
* 🪨 Coal
* 🔥 Natural gas

According to the IEA, renewables currently provide around **27% of global data-centre electricity consumption**, while coal and natural gas also remain significant sources.
[Source: IEA – Energy and AI](https://www.iea.org/reports/energy-and-ai/energy-supply-for-ai)

Increasing the share of low-carbon electricity can reduce emissions associated with data-centre power consumption.

---

## 6. ❄️ Could Cold Locations Help?

A natural question is:

> **Why not build data centres in very cold regions?**

Cold climates can make heat rejection easier and potentially reduce some cooling requirements.

However, location selection involves much more than temperature.

A data-centre location also needs:

* Reliable electricity
* Strong network connectivity
* Infrastructure
* Maintenance access
* Suitable land and facilities
* Environmental considerations

Therefore, **“colder = automatically better” is not a complete solution.**

The practical concept is:

> **Cold climate + reliable clean electricity + strong infrastructure + efficient cooling**

---

## 7. 🔥 Waste-Heat Recovery

Another important question is:

> **If GPUs generate heat, why simply throw that heat away?**

Instead, some waste heat can potentially be recovered and reused.

Possible flow:

**AI Data Centre → Waste Heat → Heat Recovery System → Buildings / District Heating**

The IEA notes that data-centre waste heat can be used in district heating systems where suitable infrastructure and proximity to heat users exist.
[Source: IEA – Opportunities for district heating](https://www.iea.org/commentaries/opportunities-for-district-heating-in-the-changing-energy-landscape)

This changes the idea from:

**Waste Heat → Environment**

to:

**Waste Heat → Useful Energy Service**

---

## 8. 🌱 Integrated Sustainable Data Centre

Rather than depending on one technology, multiple approaches can be combined.

### Proposed concept:

**Efficient AI Computing**
↓
**High-performance GPUs**
↓
**Water-efficient / closed-loop cooling**
↓
**Efficient heat exchanger**
↓
**Waste-heat recovery where feasible**

Alongside:

**Renewable / low-carbon electricity**

And, where practical:

**Cold-climate or naturally efficient heat-rejection conditions**

### Goal:

**Lower water consumption + lower energy demand + lower associated emissions + better heat utilisation**

This is not presented as a completely new technology. It is an exploration of how existing technologies and approaches could work together.

---

## 9. ⚠️ Challenges

A sustainable data-centre design still has practical challenges:

* High initial infrastructure cost
* Renewable electricity availability
* Energy storage requirements
* Grid connectivity
* Network connectivity
* Cooling-system complexity
* Maintenance requirements
* Location constraints
* Water availability
* Environmental considerations
* Waste-heat users need to be sufficiently close

Therefore, there is **no single cooling or energy solution that works everywhere**.

---

## 10. 💡 Key Insight

The environmental discussion around AI is not simply:

> **“Should we use less AI?”**

A second and important question is:

> **“Can we build the infrastructure that powers AI more efficiently?”**

This shifts the problem from only reducing demand to also improving the technology behind the demand.

---

## 11. 🎯 Conclusion

AI will continue to require computing infrastructure, electricity and cooling.

A more sustainable approach can involve combining:

**Efficient Computing**

* **Renewable / Low-Carbon Electricity**
* **Water-Efficient Cooling**
* **Closed-Loop Systems**
* **Waste-Heat Recovery**
* **Efficient Data-Centre Location**

The objective is not to eliminate AI infrastructure, but to **make the infrastructure behind AI more resource-efficient and sustainable.**

---

## 📚 References

1. International Energy Agency — **Energy and AI**
   https://www.iea.org/reports/energy-and-ai

2. International Energy Agency — **Energy Supply for AI**
   https://www.iea.org/reports/energy-and-ai/energy-supply-for-ai

3. International Energy Agency — **AI and Climate Change**
   https://www.iea.org/reports/energy-and-ai/ai-and-climate-change

4. U.S. Department of Energy — **Cooling Water Efficiency Opportunities for Federal Data Centers**
   https://www.energy.gov/cmei/femp/cooling-water-efficiency-opportunities-federal-data-centers

5. International Energy Agency — **Opportunities for District Heating in the Changing Energy Landscape**
   https://www.iea.org/commentaries/opportunities-for-district-heating-in-the-changing-energy-landscape

---

### 🔎 Disclaimer

This case study is an educational exploration of existing technologies and approaches. It does not claim to introduce a new cooling technology or a completely new data-centre design.
