
# Introduction

.. Refer to [definitions] ...

... Relation to existing IETF technologies ...

# Requirements

...

... clarify scoping is only networking ...

... add some discussion of scalability ...

# Framework

...  diagram ...

## Applications

... the transport slice system is used by an application. in most likely, that application is just another level slice orchestrator, e.g., the end-to-end slice orchestrator. but in theory it could also be an actual application that wants to manage some specific connectivity through the transport slice system. ...

## Expressing connectivity intents

... northbound interface ...

... data models ...

... SLOs as intents ...

... (most of this comes from the definitions draft) ...

## Mapping

... the requirements get mapped by a piece of software, the controller, to concrete technologies and the connectivity is set up ...

## Controller

...

##  Underlying technology

... such as MPLS or VPNs or even physical cables ...

# Considerations

## Monitoring

... we need to instrument the slice realisation to know how it is doing + update the slice as situation changes + dynamic reconfig...

## How to deal with hierarchy

...

## Security model

... accidental or malicous interaction between slices raises new security concerns ...
