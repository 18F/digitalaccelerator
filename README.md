# Digital Acquisition Pilot Guide

[![Dependency Status](https://gemnasium.com/badges/github.com/presidential-innovation-fellows/dap-guide.svg)](https://gemnasium.com/github.com/presidential-innovation-fellows/dap-guide)
[![security](https://hakiri.io/github/presidential-innovation-fellows/dap-guide/master.svg)](https://hakiri.io/github/presidential-innovation-fellows/dap-guide/master)
[![Code Climate](https://codeclimate.com/github/presidential-innovation-fellows/dap-guide/badges/gpa.svg)](https://codeclimate.com/github/presidential-innovation-fellows/dap-guide)
[![Test Coverage](https://codeclimate.com/github/presidential-innovation-fellows/dap-guide/badges/coverage.svg)](https://codeclimate.com/github/presidential-innovation-fellows/dap-guide/coverage)
[![Issue Count](https://codeclimate.com/github/presidential-innovation-fellows/dap-guide/badges/issue_count.svg)](https://codeclimate.com/github/presidential-innovation-fellows/dap-guide)

## Description

The digital acquisition pilot empowers a cross-functional team of digital and acquisition experts to shift from legacy to modern-day digital acquisition practices. Officially announced by the White House Office of Federal Procurement Policy (OFPP) in March 2016, this fully-funded project is a 5-8 month initiative to lending a team of experts from the Presidential Innovation Fellows, 18F, and U.S. Digital Service to federal agencies to train up a cadre of digital service experts.

## Setup

Clone the repo and then run `bundle install` to install the appropriate Ruby gems. Once complete, run `jekyll serve` to run the application locally.

## Deployment

This website is hosted on [cloud.gov](https://cloud.gov). Within the appropriate `org` and `space`, run `cf push <appname>` to deploy the website.