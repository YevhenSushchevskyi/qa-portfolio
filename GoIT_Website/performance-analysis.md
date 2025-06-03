# Performance Analysis – GoIT Website

## Overview
During functional testing of the GoIT website, several performance issues were identified that affected user experience, particularly on slower devices.

## Tools Used
- Chrome DevTools (Performance tab)
- Lighthouse (Chrome Extension)


## Issues Found
- Unoptimized JavaScript handlers causing UI delays when submitting forms
- Large DOM tree with redundant nested elements
- Uncompressed image assets impacting load time

## Metrics (Lighthouse Audit)
| Metric                | Before Fix | After Fix |
|-----------------------|------------|-----------|
| Performance Score     | 68         | 84        |
| First Contentful Paint| 2.9s       | 1.5s      |
| Time to Interactive   | 4.2s       | 2.3s      |

## Actions Taken
- Reported excessive DOM depth and JS reflows to developers
- Suggested image compression for key banners and thumbnails
- Monitored improvements using Lighthouse and DevTools

## Conclusion
After implementing the recommendations, page responsiveness and load time improved significantly. The revised Lighthouse score increased by approximately 24%, and perceived performance on mobile devices noticeably improved.
